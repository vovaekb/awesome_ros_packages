# Awesome ROS packages


## General 


## Messages, topics
**topic_tools**

Tools for directing, throttling, selecting, and otherwise manipulating ROS 2 topics at a meta-level. 

[github](https://github.com/ros-tooling/topic_tools)

**flex_sync**

ROS2 package with headers-only library that implements a message synchronization filter

[github](https://github.com/ros-misc-utilities/flex_sync)

## Transformations 
**angles**

This package provides a set of simple math utilities to work with angles.

[github](https://github.com/ros/angles)

## Logging
**rcl_logging_syslog**

[github](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/fujitatomoya/rcl_logging_syslog&ved=2ahUKEwjY16uqq9-MAxXFQ_EDHSVRCsUQjjh6BAgKEAE&usg=AOvVaw3Vi9GYtN_GbBUxQr6GsDxr)

[Discourse thread](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://discourse.ros.org/t/ros-2-log-system-meets-rsyslog-and-fluentbit/39280&ved=2ahUKEwjY16uqq9-MAxXFQ_EDHSVRCsUQFnoECCwQAQ&usg=AOvVaw1dRbfujPUXGrdwbKFdgGEK)

## Introspection, debugging
**ros2_tracing**

[github](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/ros2/ros2_tracing&ved=2ahUKEwjwl6uCk9-MAxXDQvEDHYv2HmQQjjh6BAgKEAE&usg=AOvVaw2YXUWIwf_nh0O9rkhi870h)

## Perception 
**mola_lidar_odometry**

[github](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/MOLAorg/mola_lidar_odometry&ved=2ahUKEwi7otnikt-MAxU6RfEDHbPELVEQjjh6BAgWEAE&usg=AOvVaw1Q7O5aQivlBnnsXEh6md6o)

**omnivision**

ROS2 package for fusing 360° equirectangular images with 3D LiDAR data.

[github](https://github.com/BlaineKTMO/omnivision)

**multisensor_calibration**

Universal calibration toolbox for assisted, target-based multi-sensor calibration. It provides a variety of methods and applications to calibrate complex multi-sensor systems (Camera-LiDAR, LiDAR-LiDAR, etc).

[github](https://github.com/FraunhoferIOSB/multisensor_calibration)

**ros2_camera_lidar_fusion**

[Discussion on discourse](https://discourse.ros.org/t/ros-2-camera-lidar-fusion-package-released/41550)

[github](https://github.com/CDonosoK/ros2_camera_lidar_fusion)

## Computer Vision
**robovision_ros2**

[github](https://github.com/ARTenshi/robovision_ros2/tree/main?tab=readme-ov-file)

## Point clouds
ROS 2 Wrapper for OpenPCDet (LIDAR-based 3D Object detection)

[github](https://github.com/pradhanshrijal/pcdet_ros2)

**pointcloud_to_grid**
[github](https://github.com/jkk-research/pointcloud_to_grid)

converts sensor_msgs/PointCloud2 LIDAR data to nav_msgs/OccupancyGrid 2D map data based on intensity and / or height.

**ros2_pcl_segmentation**
[github](https://github.com/CDonosoK/ros2_pcl_segmentation)

ROS2 Package for point cloud segmentation using PCL library. This repository contains multiple segmentation algorithms for point clouds.

## Localization, navigation 
**apriltag_detector**

This ROS 2 node uses the AprilTag library to detect AprilTags in images and publish their pose, id and additional metadata.

[github](https://github.com/christianrauch/apriltag_ros)

**wayp_plan_tools**

Waypoint and planner tools for ROS 2 with minimal dependencies.

[github](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/jkk-research/wayp_plan_tools&ved=2ahUKEwil0rL0qt-MAxUCA9sEHY3PMqYQjjh6BAgiEAE&usg=AOvVaw3n9iQt_tYo-6B5lt9VyMsl)

**Open Navigation's Nav2 Complete Coverage**

Coverage Path Planning for ROS2 Robots. Extends the Fields2Cover (F2C) library, integrating its powerful coverage algorithms into ROS 2 & Nav2 as a modular and scalable Complete Coverage Task Server.

[github](https://github.com/open-navigation/opennav_coverage)

**FlexCloud**

modular tool for direct georeferencing and drift correction of point cloud maps. It enables the georeferencing of an existing point cloud map created only from inertial sensor data (e.g. LiDAR) by the use of the corresponding GNSS data.

[github](https://github.com/TUMFTM/FlexCloud)

## Useful tools
**ros2bag_tools**

[github](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/AIT-Assistive-Autonomous-Systems/ros2bag_tools&ved=2ahUKEwiEt8X9qt-MAxX9QvEDHfCuMMIQjjh6BAgrEAE&usg=AOvVaw0xUwam50-vry_bime_V8us)

**fri - Fuzzy ROS2 Introspection**

script - wrapper around fzf to make it easier to use ROS2

[github](https://github.com/xuyuan/fri)

**ros2mock**

Tool for mocking ROS 2 services and actions.

[github](https://github.com/taDachs/ros2mock)

**ROS 2 Launch GUI**

Package provides a Graphical User Interface for ROS 2 Launch System, which allows you to visually monitor every process started by your ROS 2 launch file.

[github](https://github.com/rolker/ros2launch_gui)

**Mobile Sensor Bridge for ROS2**

Package provides a ROS2 node that streams sensor data directly from an Android smartphone, including JPEG camera streaming (up to 30 FPS), spatial pose tracking, and bidirectional audio communication


[github](https://github.com/VedantC2307/ros2-android-sensor-bridge)

## Development tools
**rsl**

RSL is a collection of C++17 utilities for ROS projects.

[github](https://github.com/PickNikRobotics/RSL)

## ROS1
**MiniROS cpp distribution**

standalone version of C++17 ROS1 client, which does not need boost, catkin or any complicated external library
[github](https://github.com/dkargin/miniroscpp)
