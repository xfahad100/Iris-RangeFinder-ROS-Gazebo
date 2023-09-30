# Iris-RangeFinder-ROS-Gazebo

I have converted sdf file for IRIS copter to xacro for ROS integration and also for connectivity with ArduPilot SITL.

If you're looking for URDF of Iris copter, you can find it in gz_launch_ros/models. 

Platforms used:
ROS version: noetic
Ubuntu 20.04
Gazebo 11

Reference: Khancyr Ardupilot Gazebo Plugin SITL

demo: https://www.youtube.com/watch?v=9cNUdmwSwrU

How to build:
just cd to src and catkin_make.

how to run:
`roslaunch gz_launch_ros distance_sensor_gazebo.launch
`

rviz: `roslaunch rviz_launch iris_rviz.launch`


![image](https://github.com/xfahad100/RangeFinder-ROS-Gazebo/assets/39211781/b3593648-1088-44c4-b3af-25fcf9c741ad)

![image](https://github.com/xfahad100/RangeFinder-ROS-Gazebo/assets/39211781/7b0f3d5e-9fe4-4cb1-bb12-73930f431b38)

