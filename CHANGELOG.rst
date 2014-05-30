^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package razer_hydra
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.21 (2014-05-29)
-------------------
* setting groovy-devel tags to increment from 0.0.20
* change ROS_INFO to ROS_DEBUG
  Conflicts:
  src/hydra.cpp
* switching driver time to use WallTime to enable using the driver with sim time.
* prefix targets during build to not collide
* Merge pull request #5 from cottsay/groovy-devel
  Use "Public Domain" license for razer_hydra
* Use "Public Domain" license for razer_hydra
* Contributors: Adam Leeper, Kel Guerin, Scott K Logan, Tully Foote

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
