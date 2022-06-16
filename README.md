# Object Detection using Laser Rangefinder UTM-30LX
## Prerequisite
- Install and configure [ROS Noetic](http://wiki.ros.org/noetic/Installation/Ubuntu) on Ubuntu 20.04 or prefered version.
- [Interface LRF with ROS](https://github.com/HUNTERVEDANSH/Interfacing-Hokuyo-Laser-in-ROS).
## Create a ROS Package in [catkin workspace](http://wiki.ros.org/catkin/Tutorials/create_a_workspace) 
```
   catkin_create_pkg OBSTACLE_DETECTION std_msgs rospy roscpp
```
- catkin_create_pkg requires that a package_name(OBSTACLE_DETECTION) and optionally a list of dependencies(std_msg roscpp rospy) on which that package depends and various other customizations.
## Create files and folders inside ros package 
- Following commands can be useded to create folders and files inside a package.
```
   cd catkin_ws
```

```
   roscd OBSTACLE_DETECTION
```

```
   mkdir src
```

```
   cd src
```

```
   gedit obs_dem.py
```
