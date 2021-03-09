SD card image files
* Pi3Noetic.1.iso : ROS Noetic on Pi3 Ubuntu 20.04 server
<p>including the following pkg :
  ubiquity_motor,
  magni_robot
  
<p>hostname: magni
<p>username: ubuntu
<p>password: ubuntu

installed wifi WPA Supplicant 
removed bloatware motd, cloud-init, apt-daily, etc.

Tips for compiling:
1. serial pkg comes from 
https://github.com/wjwwood/serial
2. remember to rosdep before catkin_make

