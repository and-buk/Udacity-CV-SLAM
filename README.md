# Project: Landmark Detection & Robot Tracking (SLAM)

This repository contains a project solution for the third project of [**Computer Vision Nanodegree program**](https://www.udacity.com/course/computer-vision-nanodegree--nd891).

### Introduction

In this project, we'll implement **SLAM (Simultaneous Localization and Mapping)** for a 2 dimensional world. We'll combine knowledge about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives us a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.

*Below is an example of a 2D robot 50x50 grid world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot.*

<p align="center">
  <img src="https://github.com/and-buk/Udacity-CV-SLAM/blob/main/images/output_example.jpg" width="500">
<p align="center">  
  <em> Example of SLAM output (estimated final robot pose and landmark location) </em>
</p>

### Instructions

The repository contains five files:

- `1. Robot Moving and Sensing.ipynb`: Robot Moving and Sensing
- `2. Omega and Xi, Constraints.ipynb`: Omega and Xi, Constraints
- `3. Landmark Detection and Trackingg.ipynb`: Landmark Detection and Tracking
- `robot_class.py`: Implementation of Robot class
- `helpers.py`: Helper functions 
