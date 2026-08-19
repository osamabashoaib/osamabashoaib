<div align="center">

# 👋 Hi, I'm Osama Ba Shoaib

### 🤖 Robotics • Computer Vision • Embedded Systems

Building robotic systems from **perception and simulation to control and real-world validation**.

<br>

![ROS2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

</div>

---

## 👨‍💻 About Me

🎓 Master 2 student in **Mechatronics, Energy and Intelligent Systems (MESI)**

🤖 Currently working in **Robotics & Computer Vision at ABMI Groupe**

💻 Interested in **robotics software, embedded systems, perception and autonomous systems**

🔧 I enjoy connecting:

**Sensors → Perception → Decision → Control → Robot**

---

# 🚀 Current Project

## 🤖 6-DoF Robotic Vision Demonstrator — ABMI Groupe

Development and integration of a **vision-guided robotic arm demonstrator**.

### 🔧 Robotics

- Integration of a robotic arm into a **ROS 2 architecture**
- Robot modelling with **URDF**
- Motion planning with **MoveIt 2**
- Controller integration
- Development of a **Digital Twin in Gazebo**

### 👁️ Computer Vision

- Camera and sensor calibration
- **Eye-to-hand / Eye-in-hand** configurations
- ArUco / ChArUco detection
- Pose estimation with **solvePnP**
- Tracking and filtering

### 🎯 Robot Control

- Vision-in-the-loop control
- Vision-guided robotic manipulation
- **Pick-and-place**
- Experimental validation on the physical robot

### 🛠️ Stack

`ROS 2` `Python` `C++` `OpenCV` `Gazebo` `MoveIt 2` `Linux`

---

# 🧩 Selected Projects

## 🗺️ TurtleBot3 Autonomous Mobile Robot

**ROS 2 • SLAM • Nav2 • Gazebo • RViz • LiDAR**

- Configured and programmed a TurtleBot3 under ROS 2
- Built real-time indoor maps using **SLAM**
- Implemented autonomous navigation between targets
- Integrated dynamic obstacle avoidance
- Tested autonomous exploration using `explore_lite`

---

## 🚗 Autonomous Maze Exploration Robot

**Raspberry Pi • Arduino • OpenCV • ArUco • Odometry • FSM**

Designed and implemented a differential-drive autonomous mobile robot capable of:

- Exploring an unknown indoor environment
- Following walls autonomously
- Detecting and avoiding obstacles
- Recording its trajectory
- Identifying the starting position using **ArUco**
- Returning toward its starting point

### Architecture

```text
Camera ──────────────┐
                     │
IR / Ultrasonic ─────┼──► Perception
                     │
Wheel Encoders ──────┘
                           │
                           ▼
                     State Machine
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
           EXPLORE    WALL FOLLOW   RETURN HOME
              │            │            │
              └────────────┼────────────┘
                           ▼
                     Motor Control
                           │
                           ▼
                        Robot
