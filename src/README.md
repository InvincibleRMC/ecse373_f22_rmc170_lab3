lab3.launch has a ```bag_type``` variable for setting which bag to run

To run robot with IMU with map and scans

```roslaunch rosbag_lab lab3.launch```

To run robot with IMU with scans and no map

```roslaunch rosbag_lab lab3.launch rviz_config:=$(find rosbag_lab)/config/scan_config.rviz```

To run robot with IMU 

```roslaunch rosbag_lab lab3.launch rviz_config:=$(find navvis_description)/config/config.rviz```

To run robot without IMU

```roslaunch navvis_description lab2.launch use_xacro:=true```