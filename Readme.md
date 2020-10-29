# ROS Driver fo Yesense IMU

## Introduction

This is a ros driver for yesense imu sensor.

## Install Dependence

Asume that you are using **ROS kinect** 

```shell
sudo apt install ros-kinetic-serial-utils ros-kinetic-serial
```

## Build

```
cd yesense_ws/
catkin_make
```

## Usage

```shell
roslaunch yesense_imu yesense.launch
```

**note: **change the params in launch to your own
