add_executable(print print.cpp)
add_dependencies(print razer_hydra)
target_link_libraries(print razer_hydra ${catkin_LIBRARIES})

add_executable(${PROJECT_NAME}_record record.cpp)
add_dependencies(${PROJECT_NAME}_record razer_hydra)
target_link_libraries(${PROJECT_NAME}_record razer_hydra ${catkin_LIBRARIES})
set_target_properties(${PROJECT_NAME}_record PROPERTIES OUTPUT_NAME record)

install(TARGETS print ${PROJECT_NAME}_record
  ARCHIVE DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION}
  LIBRARY DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION}
  RUNTIME DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
