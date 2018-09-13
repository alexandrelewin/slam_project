# Project Introduction

Welcome to Project 3! In this project you will create a 2D occupancy grid and 3D octomap from a provided simulated environment. Furthermore, you will then create your own simulated environment to map as well.


Before we get started let’s take a moment to understand where we are and why we are doing this.

After much testing and research we found RTAB-Map to be the best solution for SLAM to develop robots that can map environments in 3D. These considerations come from RTAB-Map's speed and memory management, its custom developed tools for information analysis and, most importantly, the quality of the documentation. Being able to leverage RTAB-Map with your own robots will lead to a solid foundation for mapping and localization well beyond this Nanodegree program. For this project we will be using the rtabmap_ros package, which is a ROS wrapper (API) for interacting with rtabmap. Keep this in mind when looking at the relative documentation.