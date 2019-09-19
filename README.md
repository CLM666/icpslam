# icpslam
A basic SLAM system that employs 2D and 3D LIDAR measurements


## TODO
- [X] Class for handling 6 DOF poses, with time stamp, position, rotation and covariance.
- [X] Handle robot odometry.
- [X] Handle absolute robot pose from Gazebo.
- [X] Estimate odometry using ICP on LIDAR measurements.
  - [X] Cloud skipping for coping with high frequency range measurements.
- [X] Mapping
  - [X] Implement a class to handle the current map with an Octree.
  - [X] Localization on currently built map. (inspiration: [BLAM!](https://github.com/erik-nelson/blam))
- [X] Pose graph optimization
  - [X] Abstract class for pose optimization.
  - [X] Visualization with ROS markers.
  - [X] Integrate g2o.
  - [X] Integrate GTSAM.
  - [X] Basic pose graph with ICP transforms. ("Smoothing")
  - [X] Integrate wheel odometry.
- Technical improvements
  - [ ] Make odometry, localization and mapping nodes run concurrently.
  - [ ] Make everything thread safe.
- [ ] Wiki
  - [X] Installation.
  - [X] Parameters.
  - [ ] ROS nodes.
  - [ ] Examples of use.
