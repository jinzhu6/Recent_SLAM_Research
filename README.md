
# Recent_SLAM_Research_2020
【回馈社区】跟踪SLAM前沿动态[2019](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM_Research_2019.md), [2018版](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM_Research_2018.md) .去年大概收录了500篇关于SLAM的论文，因为本人在企业重点研究的是VSLAM以及多传感器融合，所以并没有把全部论文精读，难免有漏的或者差的。今年重点是求精以及做好分类，继续做好本圈儿的服务工作。

### ------------ ICRA 2020 
### ------------ ICRA 2020 终止线 ----------
### ------------ CVPR 2020 
### ------------ CVPR 2020 终止线 ----------
### ------------ ECCV 2020 
### ------------ ECCV 2020 终止线 ----------
### ------------ IROS 2020 
### ------------ IROS 2020 终止线 ----------
### ------------ ICCV 2020 
### ------------ ICCV 2020 终止线 ----------

### SLAM
#### 1. [ Semantic SLAM ] 2020-01-13-[Visual Semantic SLAM with Landmarks for Large-Scale Outdoor Environment](https://arxiv.org/pdf/2001.01028.pdf)  Only label the point clouds with semantic segmentation info, no improvement in accuarcy. [code](https://github.com/1989Ryan/Semantic_SLAM/)
#### 2. [ Calibration ] 2020-01-13-[A Generalized Framework for Autonomous Calibration of Wheeled Mobile Robots](https://arxiv.org/pdf/2001.01555.pdf) 
#### 3. [ VSLAM ] 2020-01-13-[Trained Trajectory based Automated Parking System using Visual SLAM](https://arxiv.org/pdf/2001.02161.pdf) 
#### 4. [ Deep SLAM ] 2020-01-13-[AD-VO: SCALE-RESILIENT VISUAL ODOMETRY USING ATTENTIVE DISPARITY MAP](https://arxiv.org/pdf/2001.02090.pdf)  Learned based frame to frame VO with the input as disparity map.
#### 5. [ Lidar Deep SLAM ] 2020-01-13-[CAE-LO: LiDAR Odometry Leveraging Fully Unsupervised Convolutional Auto-Encoder for Interest Point Detection and Feature Description](https://arxiv.org/pdf/2001.01354.pdf) Auto-Encoder based LiDAR Odometry (CAE-LO) that detects interest points from spherical ring data using 2D CAE and extracts features from multi-resolution voxel model using 3D CAE.  [code](https://github.com/SRainGit/CAE-LO) 
#### 6. [ VSLAM ] 2020-01-13-[Good Feature Matching: Towards Accurate, Robust VO/VSLAM with Low Latency](https://arxiv.org/pdf/2001.00714.pdf) Introduction of an efficient good feature selection algorithm using the Max-logDet metric, which is an order of magnitude faster than state-of-the-art feature selection approaches. [code](https://github.com/ivalab/GF_ORB_SLAM)  
#### 7. [ VSLAM ] 2020-01-13-[Direct Sparse Visual-Inertial Odometry with Stereo Cameras](https://candyguo.github.io/files/1.pdf) Quantitative evaluation demonstrates that the proposed Stereo VI-DSO is superior to Stereo DSO both in terms of tracking accuracy and robustness. But the result is worse than VINS.
#### 8. [ VSLAM ] 2020-01-14-[Accurate Line Reconstruction for Point and Line-Based Stereo Visual Odometry](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8936964) 
#### 9. [ VSLAM ] 2020-01-14-[A Stereo Visual-Inertial SLAM Approach for Indoor Mobile Robots in Unknown Environments Without Occlusions](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8937551) Use one-circle feature-matching method, which refers to a sequence of the circle matching for the time after space (STCM), and an STCM-based visual-inertial simultaneous localization and mapping (STCM-SLAM) technique.
#### 10. [ Lidar Seg ] 2020-01-14-[Multi-Scale Point-Wise Convolutional Neural Networks for 3D Object Segmentation From LiDAR Point Clouds in Large-Scale Environments](https://ieeexplore.ieee.org/abstract/document/8943956/authors#authors) 
#### 11. [ Review ] 2020-01-14-[Multi-Sensor Fusion in Automated Driving: A Survey](https://sci-hub.tw/10.1109/ACCESS.2019.2962554) 
#### 12. [ Lidar Deep SLAM ] 2020-01-14-[SLOAM: Semantic Lidar Odometry and Mapping for Forest Inventory](https://arxiv.org/pdf/1912.12726.pdf) 
#### 13. [ Deep SLAM ] 2020-01-22-[Learning Topometric Semantic Maps from Occupancy Grids](https://arxiv.org/pdf/2001.03676.pdf) 2D laser semantic map. 
#### 14. [ VSLAM ] 2020-01-22-[Temporal Delay Estimation of Sparse Direct Visual Inertial Odometry for Mobile Robots](https://sci-hub.tw/https://doi.org/10.1016/j.jfranklin.2019.11.075) Calibrate the time offset between IMU and Camera.

### 3D Reconstruction
#### 1. [Automatically explore] 2020-01-14-[Plan3D: Viewpoint and Trajectory Optimization for Aerial Multi-View Stereo Reconstruction](https://sci-hub.tw/https://doi.org/10.1145/3233794)

### Path Planning
#### 1. [UAV] 2020-01-14-[Robust Real-time UAV Replanning Using Guided Gradient-based Optimization and Topological Paths](https://arxiv.org/pdf/1912.12644.pdf)Replanning method based on GTO.[code](https://github.com/HKUST-Aerial-Robotics/Fast-Planner)
#### 2. [Auto exploration] 2020-01-14-[3D Exploration and Navigation with Optimal-RRT Planners for Ground Robots in Indoor Incidents](https://www.researchgate.net/publication/338367746_3D_Exploration_and_Navigation_with_Optimal-RRT_Planners_for_Ground_Robots_in_Indoor_Incidents)

### Others.

## SLAM 能力图 

<img src="https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM%E8%83%BD%E5%8A%9B%E5%9B%BE.png" width ="300" height="550" />





























