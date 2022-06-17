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
- Change directory to catkin_ws
```
   cd catkin_ws
```
- Switch to the respective package in the wprkspace 
```
   roscd OBSTACLE_DETECTION
```
- Create a folder named 'src' to store the python scripts
```
   mkdir src
```
- Change to src folder
```
   cd src
```
- Use gedit command create and store the required python file
```
   gedit obs_dem.py
```
- Code for [obs_dem.py](https://github.com/HUNTERVEDANSH/Object-Detection-using-Laser-Rangefinder-UTM-30LX-/blob/main/OBSTACLE_DETECTION/src/obs_dect.py)
- **For more info related to obtacle detection checkout the OBSTACLE_DETECTION package in the code section**
