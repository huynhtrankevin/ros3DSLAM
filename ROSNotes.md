##Start up##
1) terminal bash already configured to source ROS installation
http://wiki.ros.org/noetic/Installation/Ubuntu

2) Run the following to be able to use ROS tools
```
sudo rosdep init
rosdep update
```

3) Create a catkin workspace to contain related packages and source the bash file in devel folder
```
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make
```


