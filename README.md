# Awesome-NN-SLAM

**:running::running::running:Under initial construction.**

**If you find something wrong or want to add something new, don't hesitate to make an issue or a PR.**

This repo is used to record algorithms constructed by neural networks, either about a complete SLAM system, or part of it. 

For each paper, we should answer the following questions:
- What **problems** does it solve?
- What **methods** does it propose?
- How are the **results**?
- What **challenges** or **deficiencies** does it face?
- **Where** is it published? **Who** are the authors?

In addition, some related resources, such as hyperlinks to open-source codes and PDF files, are also welcome.

Topics & Quick jump: 
  - [SLAM System](#slam-system)
  - [Unsupervised Structure-from-Motion](#unsupervised-structure-from-motion)
  - [Depth Estimation](#depth-estimation)
  - [Visual Odometry](#visual-odometry)
  - [Visual-Inertial Odometry](#visual-inertial-odometry)
  - [Feature Representation](#feature-representation)
  - [Camera Location](#camera-location)
  - [Place Recognition (Loop Detection)](#place-recognition-loop-detection)
  - [Mapping and Map Compression](#mapping-and-map-compression)
  - [Optimization](#optimization)

## SLAM System
### 2019
- **[ICRA 2019]** GEN-SLAM: Generative Modeling for Monocular Simultaneous Localization and Mapping
### 2017
- **[CVPR 2017]** CNN-SLAM: Real-time dense monocular SLAM with learned depth prediction

[Back to top](#awesome-nn-slam)

## Self-supervised Structure-from-Motion
### 2019
- **[Arxiv 2019]** Flow-Motion and Depth Network for Monocular Stereo and Beyond
- **[IROS 2019]** Learning Residual Flow as Dynamic Motion from Stereo Videos
- **[NeurIPS 2019]** Unsupervised Scale-consistent Depth and Ego-motion Learning from Monocular Video
- **[ICCV 2019]** Self-Supervised Monocular Depth Hints
- **[ICCV 2019]** Depth from Videos in the Wild: Unsupervised Monocular Depth Learning from Unknown Cameras
- **[ICRA 2019]** Unsupervised Learning of Monocular Depth and Ego-Motion Using Multiple Masks
- **[ICRA 2019]** GANVO - Unsupervised Deep Monocular Visual Odometry and Depth Estimation with Generative Adversarial Networks
- **[CVPR 2019]** Competitive Collaboration: Joint Unsupervised Learning of Depth, Camera Motion, Optical Flow and Motion Segmentation
- **[CVPR 2019]** UnOS: Unified Unsupervised Optical-flow and Stereo-depth Estimation by Watching Videos
- **[AAAI 2019]** Depth Prediction Without the Sensors: Leveraging Structure for Unsupervised Learning from Monocular Videos
### 2018
- **[ECCV 2018]** DF-Net: Unsupervised Joint Learning of Depth and Flow using Cross-Task Consistency
- **[CVPR 2018]** Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction
- **[CVPR 2018]** GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose
- **[IROS 2018]** UnDEMoN: Unsupervised Deep Network for Depth and Ego-Motion Estimation
### 2017
- **[CVPR 2017]** Unsupervised Learning of Depth and Ego-Motion from Video 

[Back to top](#awesome-nn-slam)

## Depth Estimation
### 2019
- **[TPAMI 2019]** Progressive Fusion for Unsupervised Binocular Depth Estimation using Cycled Networks
- **[ICCV 2019]** Digging into self-supervised monocular depth estimation
- **[CVPR 2019]** Learning Monocular Depth Estimation Infusing Traditional Stereo Knowledge
- **[CVPR 2019]** CAM-Convs: Camera-Aware Multi-Scale Convolutions for Single-View Depth
- **[CVPR 2019]** Veritatem Dies Aperit-Temporally Consistent Depth Prediction Enabled by a Multi-Task Geometric and Semantic Scene Understanding Approach
- **[CVPR 2019]** Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving
- **[CVPR 2019]** Bilateral Cyclic Constraint and Adaptive Regularization for Unsupervised Monocular Depth Prediction
- **[CVPR 2019]** Towards Scene Understanding: Unsupervised Monocular Depth Estimation with Semantic-aware Representation
- **[CVPR 2019]** Geometry-Aware Symmetric Domain Adaptation for Monocular Depth Estimation
- **[CVPR 2019]** Recurrent MVSNet for High-resolution Multi-view Stereo Depth Inference
- **[CVPR 2019]** Refine and Distill: Exploiting Cycle-Inconsistency and Knowledge Distillation for Unsupervised Monocular Depth Estimation
- **[CVPR 2019]** Neural RGB->D Sensing: Depth and Uncertainty from a Video Camera
- **[CoRR 2019]** Attention-based Context Aggregation Network for Monocular Depth Estimation

### 2018

- **[ICRA 2018]** Just-in-Time Reconstruction: Inpainting Sparse Maps Using Single View Depth Predictors as Priors
- **[CVPR 2018]** Learning for Disparity Estimation through Feature Constancy

- **[CVPR 2018]** Deep Ordinal Regression Network for Monocular Depth Estimation
- **[CVPR 2018]** Learning Depth from Monocular Videos using Direct Methods
- **[CVPR 2018]** Structured Attention Guided Convolutional Neural Fields for Monocular Depth Estimation
- **[CVPR 2018 Workshop]** On the Importance of Stereo for Accurate Depth Estimation: An Efficient Semi-Supervised Deep Neural Network Approach
- **[ECCV 2018]** Learning Monocular Depth by Distilling Cross-domain Stereo Networks
- **[ECCV 2018]** Look Deeper into Depth: Monocular Depth Estimation with Semantic Booster and Attention-Driven Loss

### 2017
- **[ICCV 2017]** End-to-End Learning of Geometry and Context for Deep Stereo Regression
- **[CVPR 2017]** Unsupervised Monocular Depth Estimation with Left-Right Consistency

### 2016 and before
- **[ECCV 2016]** Unsupervised CNN for Single View Depth Estimation: Geometry to the Rescue
- **[NeurIPS 2014]** Depth Map Prediction from a Single Image Using a Multi-scale Deep Network

[Back to top](#awesome-nn-slam)

## Visual Odometry
### 2019
- **[CVPR 2019]** MagicVO: End-to-End Monocular Visual Odometry through Deep Bi-directional Recurrent Convolutional Neural Network
- **[CVPR 2019]** Understanding the Limitations of CNN-based Absolute Camera Pose Regression
- **[CVPR 2019]** Beyond Tracking: Selecting Memory and Refining Poses for Deep Visual Odometry
- **[ICRA 2019]** Learning Monocular Visual Odometry through Geometry-Aware Curriculum Learning

### 2018
- **[ICRA 2018]** Deep Auxiliary Learning for Visual Localization and Odometry
- **[ICRA 2018]** UnDeepVO: Monocular Visual Odometry through Unsupervised Deep Learning
- **[CVPR 2018 Workshop]** Geometric Consistency for Self-Supervised End-to-End Visual Odometry
- **[IJRR 2018]** End-to-end, sequence-to-sequence probabilistic visual odometry through deep neural networks

### 2017
- **[ICRA 2017]** DeepVO: Towards end-to-end visual odometry with deep Recurrent Convolutional Neural Networks
- **[IROS 2017]** Deep regression for monocular camera-based 6-DoF global localization in outdoor environments

[Back to top](#awesome-nn-slam)

## Visual-Inertial Odometry
### 2019
- **[CVPR 2019]** Selective Sensor Fusion for Neural Visual-Inertial Odometry 

### 2018
- **[IROS 2018]** Vision-Aided Absolute Trajectory Estimation Using an Unsupervised Deep Network with Online 

### 2017
- **[AAAI 2017]** VINet: Visual-Inertial Odometry as a Sequence-to-Sequence Learning ProblemError Correction

[Back to top](#awesome-nn-slam)

## Feature Representation
### 2019
- **[3DV 2019]** SIPs: Succinct Interest Points from Unsupervised Inlierness Probability Learning

### 2018
- **[CVPR 2018 Workshop]** SuperPoint: Self-Supervised Interest Point Detection and Description

[Back to top](#awesome-nn-slam)

## Camera Location
### 2019
- **[Arxiv 2019]** AtLoc: Attention Guided Camera Localization
- **[Arxiv 2019]** Hierarchical Joint Scene Coordinate Classification and Regression for Visual Localization
### 2018

- **[ICRA 2018]** Deep Auxiliary Learning for Visual Localization and Odometry

### 2017

- **[IROS 2017]** Deep regression for monocular camera-based 6-DoF global localization in outdoor environments

### 2016 and before
- **[ICCV 2015]** PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization

[Back to top](#awesome-nn-slam)

## Place Recognition (Loop Detection)
### 2016 and before
- **[CVPR 2016]** NetVLAD: CNN Architecture for Weakly Supervised Place Recognition

[Back to top](#awesome-nn-slam)

## Mapping and Map Compression

[Back to top](#awesome-nn-slam)

## Optimization

[Back to top](#awesome-nn-slam)