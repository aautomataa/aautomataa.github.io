---
layout: archive
title: "Research Projects"
permalink: /researchprojects/
author_profile: true
# redirect_from: 
#   - /researchprojects/
---

* Oct-Dec 2024: Implementation of Forward Collision Speed Warning System Based on YOLOv10 and DeepSORT
  * Independent Project | Advisor: Associate Prof. Ge Song
  * Designed and implemented a forward collision warning system for autonomous driving using
YOLOv10(state-of-the-art object detection) and DeepSORT(object tracking), achieving real-time
detection and tracking of vehicles (e.g., cars, trucks, buses) and calculating collision risks based on
distance, relative speed, and human reaction time.
  * Developed a distance measurement algorithm based on geometric optics and similarity triangle
principles, and a speed estimation algorithm by mapping real-world distances to pixel distances using
detection and tracking results.
  * Enhanced the system by replacing the Partial Self-Attention (PSA) module in YOLOv10 with Spatial and
Channel Synergistic Attention (SCSA), improving precision by 2% across all categories while
maintaining high recall and mAP.
  * Trained the model on NVIDIA RTX 4090 GPU, achieving over 91% precision (96% for cars) and high
mAP50-95 metrics.

* Jun-Jul 2023: Fall Detection System and Alarm Device for The Elderly Based on STM32Cube.Al
  * Leader | Advisor: Associate Prof. Fei Xie, School of Electrical and Automation Engineering, NNU
  * Aimed to develop a video analysis system based on the MCU/MPU development board developed by
STMicroelectronics and advanced algorithms of machine learning and computer vision and deploy it on
the STM32 embedded development board.
  * Completed the key point detection algorithm YOLOv7-POSE; took video as input and used the
YOLOv7-POSE model (accuracy rate 88.27%) to scan each frame of the video.
  * Implemented the hardware deployment of the STM32 development board using Python's pySerial
library and serial communication between the Python program and STM32.

* Sept 2023: Optimal Design of Heliostat Field Based on PSO Algorithm
  * Core Member | China Undergraduate Mathematical Contest in Modeling
  * Utilized Python to model heliostat field: developed two occlusion models (an occlusion recognition
model based on octree and an occlusion area model based on projected area under parallel light
irradiation).
  * Built an optimization model for various parameters of the mirror field based on the Particle Swarm
Optimization (PSO) algorithm.
  * Drew the field graphics and related data points using MATLAB and wrote the thesis using LaTex.
