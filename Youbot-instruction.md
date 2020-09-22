# Youbot WIFI RSSI localization manual

###Hardware
Push and hold the power button on the robot 3 times. First until "Swit". Second time until "PC on" then release. Third time until "Motor on" then release.
For turning off, push and hold the switch 3 times similar to the steps above to turn off the motors, the PC and then complete switch off. 

It is best to use Terminator to have 4 terminals. The terminal order below is denoted followed by the command.

* 1st: 
  'ssh youbot@<the-ip-address-of-the-robot>', this will use SSH to access and control a machine remotely.
* 1st: 
  roslaunch youbot_navigation youbot_init.launch
* 2nd: roslaunch youbot_navigation static_map_amcl.launch

Run Rviz, a monitoring program for ROS

* 3rd: rosrun rviz rviz
