
# SLAM-with-Intel-Realsense-L515

RTAB-Map (Real-Time Appearance-Based Mapping) is a open-source framework for Simultaneous Localization and Mapping (SLAM) that is designed to work with RGB-D (color and depth) sensor data. Intel Realsense L515 is used in this project.


## Prerequisites

### 1.1 **Ubuntu** and **ROS**

Ubuntu 64-bit 20.04.

ROS noetic. [ROS Installation](https://wiki.ros.org/noetic/Installation/Ubuntu)

### 1.2 **realsense2_camera**

[realsense2_camera](https://github.com/IntelRealSense/realsense-ros)


### 1.3 **imu_filter_madgwick**

```bash
$ sudo apt-get install ros-noetic-imu-filter-madgwick

```
### 1.3 **RTABmap_ros**

```bash
$ sudo apt-get install ros-noetic-rtabmap-ros

```
### 1.4 **Robot_localization**

```bash
$ sudo apt-get install ros-noetic-robot-localization

```
## 2. Launch ROS
if you would like to create the map
```
    roslaunch realsense2_camera opensource_tracking.launch
```

## 3. Sensor Setup
If you have new Realsense L515 sensor, you may follow the below setup instructions

    