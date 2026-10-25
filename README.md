## Hi, I'm Siddharth

I build software for robots that run on real hardware: perception, SLAM and state estimation, and robot learning. I'm finishing an M.S. in ECE (Intelligent Systems, Robotics & Control) at UC San Diego in March 2027, and I'm looking for full-time robotics software roles starting April 2027.

- **Amazon Robotics** (SDE intern, 2026): a production C++ library that validates, dispatches and tracks robot skills over ROS 2, and a VLM prototype that turns commands into executed robot skills.
- **Addverb Robotics** (robotics engineer, 2023-2025): lead architect of the 6-DoF pose estimation pipeline from raw point clouds on warehouse robots, deployed at customer sites.
- **UC San Diego ARClab** (research): sim-to-real reinforcement learning for dexterous grasping on real Inspire and Wuji hands.

[Website](https://siddharthramasushil.github.io/) · [LinkedIn](https://www.linkedin.com/in/siddharth-rs/) · [Medium](https://medium.com/@siddharthramasushil) · sramasushil@ucsd.edu

### Projects

| | |
|---|---|
| <img src="https://github.com/daatsi-aeres/plane_segmentation_tool/raw/main/assets/fullscene.gif" width="400"> | **[plane_segmentation_tool](https://github.com/daatsi-aeres/plane_segmentation_tool)** · C++17, PCL<br>6-DoF pose of box faces from raw depth point clouds: RANSAC, clustering, MLS, minimum-area rectangle. Tested, benchmarked, CI. The open-source core of my warehouse picking pipeline. |
| <img src="https://github.com/daatsi-aeres/robust-orb-slam3/raw/master/assets/glare_tracking.gif" width="400"> | **[robust-orb-slam3](https://github.com/daatsi-aeres/robust-orb-slam3)** · C++, OpenCV, RealSense<br>Adaptive CLAHE, guided filtering and IMU-guided deblurring in front of ORB-SLAM3. 23% less time in degraded tracking under glare. |
| <img src="https://github.com/daatsi-aeres/smolvam/raw/main/assets/rollouts.gif" width="400"> | **[smolvam](https://github.com/daatsi-aeres/smolvam)** · PyTorch, MuJoCo<br>Robot control from a small video model: LoRA-tuned image-to-video generator plus a flow-matching action head. ~60% cube-stacking success end to end. |
| <img src="https://github.com/daatsi-aeres/multimodal-slam/raw/main/assets/lidar_occupancy.gif" width="400"> | **[multimodal-slam](https://github.com/daatsi-aeres/multimodal-slam)** · Python, GTSAM<br>LiDAR SLAM with ICP and loop closure, EKF visual-inertial SLAM on SE(3), IMU orientation tracking with panorama stitching. |
| <img src="https://github.com/daatsi-aeres/home-tidying-robot/raw/main/assets/demo.gif" width="400"> | **[home-tidying-robot](https://github.com/daatsi-aeres/home-tidying-robot)** · ROS 2, Nav2, Gazebo<br>A custom mobile manipulator that tidies a two-room home autonomously. |
| <img src="https://github.com/daatsi-aeres/vo-frontend/raw/main/assets/frontend_tracking.gif" width="400"> | **[vo-frontend](https://github.com/daatsi-aeres/vo-frontend)** · C++17, OpenCV, Eigen<br>Monocular visual odometry front end from scratch: ORB, essential matrix, triangulation, PnP tracking. |
| <img src="https://github.com/daatsi-aeres/epipolar-visualizer/raw/main/assets/epilines.gif" width="400"> | **[epipolar-visualizer](https://github.com/daatsi-aeres/epipolar-visualizer)** · C++, OpenCV<br>Interactive tool for two-view geometry: features, matches and epipolar lines update live as you tune parameters. |

### Toolbox

C++ (14/17), Python · ROS 2, DDS · PCL, OpenCV, Eigen, GTSAM · PyTorch · Isaac Sim, MuJoCo, Gazebo · Docker, CI/CD · Jetson, ARM64, RealSense, LiDAR, IMU
