# 6-DOF Robotic Arm 🤖

![ROS2](https://img.shields.io/badge/ROS2-Humble-blue)
![MoveIt](https://img.shields.io/badge/MoveIt-Motion%20Planning-green)
![Gazebo](https://img.shields.io/badge/Gazebo-Ignition%206-orange)
![C++](https://img.shields.io/badge/Language-C%2B%2B-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
This project demonstrates the **simulation, motion planning, and control of a 6-Degree-of-Freedom (6-DOF) robotic arm** using **ROS 2 Humble**, **MoveIt**, and **Ignition Gazebo**.  
The robotic arm executes predefined poses based on **user numeric input**, showcasing autonomous manipulation and trajectory planning in a simulated environment.

---

## 🛠️ Tech Stack
- **ROS 2 Humble**
- **MoveIt 2**
- **Ignition Gazebo 6**
- **C++**
- Robot Description (URDF/Xacro)
- Motion Planning & Control

---

## 📦 Prerequisites
Make sure the following are installed:

- ROS 2 **Humble**
- Ignition **Gazebo 6**
- MoveIt 2
- `arduinobot_description`
- `arduinobot_controller`
- `arduinobot_moveit`

---

## ▶️ Running the Simulation

### Launch Files (Step-by-Step)
```bash
ros2 launch arduinobot_description gazebo.launch.py
ros2 launch arduinobot_controller controller.launch.py
ros2 launch arduinobot_moveit moveit.launch.py

## You can launch simulation either with above 3 launch files or with below single launch file

ros2 launch arduinobot_moveit arduinobot_simulation.launch.py

## Script
ros2 run arduinobot_moveit simple_moveit_interface

