# ROS 2 URDF 4-DOF Industrial Robotic Arm

## Overview

This project presents the design and implementation of a **4-DOF industrial robotic arm using ROS 2, URDF/Xacro, RViz2, and Gazebo**.

Two versions of the robotic arm were developed:

1. **Basic 4-DOF URDF Model** – developed to verify the robot structure, links, revolute joints, RViz visualization, and TF tree.
2. **Upgraded 4-DOF Xacro Model** – enhanced with inertial properties, a wrist assembly, and a two-finger gripper, followed by visualization and simulation in Gazebo.

## Features

- 4-DOF robotic arm
- URDF and Xacro modeling
- Revolute joints with joint limits
- Visual and collision geometry
- Inertial properties
- Wrist assembly
- Two-finger gripper
- RViz2 visualization
- TF tree verification
- Gazebo simulation
- ROS 2 launch files

## Robot Structure

The main arm consists of:

```text
base_link
    |
  joint1
    |
  link1
    |
  joint2
    |
  link2
    |
  joint3
    |
  link3
    |
  joint4
    |
  link4
    |
 wrist_link
    |
 gripper_base
   /     \
left     right
finger   finger
