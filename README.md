# rtabmap_livox
ROS 2 package to launch RTAB-Map with the Leo Rover simulation of SpaceR using a 3D LiDAR.

To install RTAB-Map on ROS 2 Humble, use the following command:

```bash
sudo apt install ros-humble-rtabmap-ros
```

To run RTAB-Map with the Livox MID 360 LiDAR, or the simulated sensor in Gazebo, in combination with the Leo Rover, run the following command:

```bash
ros2 launch rtabmap_livox rtabmap_livox.launch.py
```
