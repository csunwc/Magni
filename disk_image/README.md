My Magni robot Pi3 SD card image files
* Pi3Noetic.1.iso : includes ubiquity_motor, magni_robot
  
Ubuntu baseline: 20.04 server (64 bit), ROS Noetic 
* installed wifi WPA Supplicant (edit /etc/wpa_supplicant.conf)
* removed bloatware motd, cloud-init, apt-daily, etc.

Initial login:
* SSH via wired LAN or monitor-keyboard hookup
* hostname: magni
* username: ubuntu
* password: ubuntu

Tips for compiling:
1. serial pkg comes from 
https://github.com/wjwwood/serial
2. remember to rosdep before catkin_make
