^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package razer_hydra
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2014-05-29)
------------------
* setting hydro-devel to 0.1.x tags
* update changelog
* fix CMake formatting
* change ROS_INFO to ROS_DEBUG
  Conflicts:
  src/hydra.cpp
* Merge commit 'fbced1dda9972f3c54ccee8c61dae6993285ed8b' into hydro-devel
* fix license tag in package.xml
* switching driver time to use WallTime to enable using the driver with sim time.
* apply catkin_lint
* Use "Public Domain" license for razer_hydra
  Source files in the project state that the code is Public Domain
* 0.0.12
* fixed install target
* udev filename -> hydro
* Contributors: Adam Leeper, David Gossow, Kel Guerin, Scott K Logan, Tully Foote

0.0.5 (2013-07-04)
------------------
* actually updated the changelog

0.0.4 (2013-07-04)
------------------
* adds pkg-config to package.xml

0.0.3 (2013-07-02)
------------------
* fixed libusb depends

0.0.2 (2013-07-01)
------------------
* adds changelog
* fixes launch files
* fixes install paths

0.0.1 (2013-06-21)
------------------
* implemented filters
* adds offset pivot and grab frame
* adds gencpp build dependency to target
* fixed node name in launch file
* updated to new message name
* adds new udev rules (courtesy Ingo Kresse)
* initial port from jks-ros-pkg
