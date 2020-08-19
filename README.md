# urg_node_my_config
 urg_node for Hokuyo lidar

This project is clone from [urg_node](https://github.com/ros-drivers/urg_node), [driver_common](https://github.com/ros-drivers/driver_common), [laser_proc](https://github.com/ros-perception/laser_proc) and [urg_c](https://github.com/ros-drivers/urg_c).

I modified them according to my needs.

## Update

- 2020.8.19  It can set scan topic by rosparam:scan_topic.

## Usage

- git clone this project to ros_ws/src

- `catkin_make`

- Remember to set your Ethernet Address to 192.168.0.20 (As long as it is not 192.168.0.10) and set Netmask to 255.255.255.0 (or 24). You can leave Gateway void.

- you can `ping 192.168.0.10` to test. 