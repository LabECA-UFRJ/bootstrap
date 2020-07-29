# LABECA - ROS Vehicle Testbed

## ROS installation
Follow [Melodic installation](http://wiki.ros.org/melodic/Installation/Ubuntu) for Ubuntu 18.04.

## Clone required repositories
Clone the repositories from [LabECA-UFRJ](https://github.com/LabECA-UFRJ/). 

Some repositories have additional dependencies, e.g. [camera_to_fixed_frame](https://github.com/LabECA-UFRJ/camera_to_fixed_frame) requires the aruco [package](https://github.com/pal-robotics/aruco_ros). Refer to each package's documentation for all dependencies.

## Running
The repository [robot_launchers](https://github.com/LabECA-UFRJ/robot_launchers) has examples of launchers that can be used with roslaunch command line tool:
```
roslaunch robot_launchers example.launch
```
