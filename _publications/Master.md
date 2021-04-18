---
title: "Research on Loop Closure Detection Based on Semantic Information"
collection: publications
permalink: /publication/Master
data: 2020-7-5

citation: '<b>Yachen Zhu</b>  <i>MSc thesis.</i>'
---



[[paper]](https://zhuyachen.github.io/files/18214872.pdf)


## Abstract

In recent years, Artificial Intelligence has important research 
value in various fields. Among them, robotics, which is a 
representative of high technology, has also become a key research area. 
The robot must first be able to autonomously sense the surrounding 
environment information and accurately locate its own position, which 
is also the prerequisite for the robot to be able to autonomously 
navigate and move. Therefore, Simultaneous Localization And Mapping 
(SLAM) is an important research topic. However, to perform high
precision SLAM, a high-performance loop closure detection module is 
essential. The loop closure detection module can significantly reduce 
the localization drift caused by the front-end odometry. But it is very 
challenging to design a loop closure detection algorithm with high 
detection accuracy under high recall. The method proposed in this 
thesis uses lidar as the main sensor to quickly and robustly detect 
whether there is a loop closure by detecting semantic information in 
the environment and then extracting global descriptors and local 
descriptors.

The work of this thesis mainly includes the following aspects:
(1) This thesis proposes a loop closure detection method based on 
object level using only LiDAR data in an urban driving environment. 
This method innovatively extracts the point cloud descriptor from the 
semantic information in the scene, and enhances the point cloud 
descriptor's ability to describe the object. At the same time, the 
method in this thesis improves the efficiency of detecting loops based 
on the idea of searching from coarse to fine.
(2) Combining graph theory and semantic information, this thesis
proposes two graph-based descriptors, one belongs to the global 
descriptor and has the necessary rotation invariance for loop detection, 
which is used to construct kd-tree and quickly find and loop candidate 
point clouds similar with the query one; the other belongs to the local 
descriptor, which is used to calculate the one-to-one correspondence
relationship between the semantic objects between the two point clouds 
and handle the data association problem.
(3) This thesis studies four other traditional loop closure
detection methods and conducts a large number of experimental 
comparisons with the method proposed in this thesis on the large public 
KITTI dataset, and verifies many aspects of this method compared with 
other traditional loop closure detection methods.

