#### LOAM modifications

##### [LOAM: Lidar Odometry and Mapping, 2014, CMU](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwik_aTXtsfqAhVV6aYKHR6fBvkQFjAAegQIAxAB&url=https%3A%2F%2Fri.cmu.edu%2Fpub_files%2F2014%2F7%2FJi_LidarMapping_RSS2014_v8.pdf&usg=AOvVaw0hfxbqKN8XjqaEevBH-34Q)

[Detailed version of the paper in Springer (2017)](https://www.researchgate.net/publication/295079642_Low-drift_and_Real-time_Lidar_Odometry_and_Mapping) 

Implementations

|                             Repo                             | Comment                                                      |                            Stars                             |                         Last update                          |
| :----------------------------------------------------------: | :----------------------------------------------------------- | :----------------------------------------------------------: | :----------------------------------------------------------: |
| [loam_velodyne](https://github.com/laboshinl/loam_velodyne)  | ROS<br />VLP-16 + IMU (optional)                             | ![](https://img.shields.io/github/stars/laboshinl/loam_velodyne?style=social) | ![](https://img.shields.io/github/last-commit/laboshinl/loam_velodyne) |
| [loam_velodyne_kitti_ros](https://github.com/claydergc/loam_velodyne_kitti_ros) | ROS<br />KITTI (HDL-64)                                      | ![](https://img.shields.io/github/stars/claydergc/loam_velodyne_kitti_ros?style=social) | ![](https://img.shields.io/github/last-commit/claydergc/loam_velodyne_kitti_ros) |
|   [LOAM_NOTED](https://github.com/cuitaixiang/LOAM_NOTED/)   | Repo with detailed Chinese comments on the code              | ![](https://img.shields.io/github/stars/cuitaixiang/LOAM_NOTED?style=social) | ![](https://img.shields.io/github/last-commit/cuitaixiang/LOAM_NOTED) |
|  [A-LOAM ](https://github.com/HKUST-Aerial-Robotics/A-LOAM)  | (Advanced implementation for LOAM)<br />Supports VLP-16, HDL-32 and HDL-64. A-LOAM is an Advanced implementation of LOAM (J. Zhang and S. Singh.  LOAM: Lidar Odometry and Mapping in Real-time), which uses Eigen and  Ceres Solver to simplify code structure. | ![](https://img.shields.io/github/stars/HKUST-Aerial-Robotics/A-LOAM?style=social) | ![](https://img.shields.io/github/last-commit/HKUST-Aerial-Robotics/A-LOAM) |

##### V-LOAM: Visual-Lidar Odometry and Mapping, 2015, CMU

[Paper](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiKhK6qucfqAhVuyaYKHQ7ACtAQFjAAegQIBBAB&url=https%3A%2F%2Ffrc.ri.cmu.edu%2F~zhangji%2Fpublications%2FICRA_2015.pdf&usg=AOvVaw1--0dBT4Nt5ohn_Ep9V095)

No implementation provided

##### LeGO-LOAM: Lightweight and Ground-Optimized Lidar Odometry and Mapping, 2018, Stevens Institute of Technology

Uses semantic segmentation of ground and objects, uses gtsam

[Paper](https://ieeexplore.ieee.org/document/8594299)

[Original implementation](https://github.com/ RobustFieldAutonomyLab/LeGO-LOAM) Works with VLP-16

##### LIOM: Tightly Coupled 3D Lidar Inertial Odometry and Mapping, 2019, Hong Kong University of Science and Technology

LiDAR + IMU

Uses LOAM as basis and IMU for joint optimizations

[Paper](https://arxiv.org/abs/1904.06993)

[Original code](https://github.com/hyye/lio-mapping)

##### LIO-SAM: Tightly-coupled Lidar Inertial Odometry via Smoothing and Mapping, 2020, MIT

LiDAR + IMU + GPS (optionally)

Paper

[Original implementation](https://github.com/TixiaoShan/LIO-SAM)