# Neural-Network-Based-ERG for the ViperX-300 6-DoF Robotic Manipulator
This repository contains the full control stack for the **Interbotix ViperX-300 6-DoF robotic manipulator**, leveraging a **Neural Network-based Explicit Reference Governor (NN-ERG)** for safe and stable trajectory tracking. The control architecture integrates **Python-based ROS2 nodes**, **MATLAB-based dynamics**, and **TCP/IP server communication** between Linux (WSL2) and Windows.


# 🛠️ Experimental Setup

- **Robot**: Interbotix ViperX-300 6-DoF robotic manipulator
- **Control Method**: Neural Network-based Explicit Reference Governor (NN-ERG)
- **Operating System**:
  - Linux: Ubuntu 22.04 (via WSL2)
  - Windows 10/11 with MATLAB support

- **Frameworks**:
  - ROS2 (Humble)
  - Python 3.10+
  - MATLAB (for mass matrix computation)



## 🧠 Key Features

- ✅ **Neural Network-based Explicit Reference Governor** for constraint handling  
- ✅ **Real-time Gravity Compensation**
- ✅ **Forward and Inverse Kinematics Implementations**
- ✅ **Mass-Inertia Matrix Calculation using MATLAB**
- ✅ **TCP/IP Server-Client Communication** between Python (ROS2) and MATLAB


## 🎥 Demo Video

Watch the experimental results here: [YouTube Video](https://www.youtube.com/watch?v=C7nhoAOrIeo)
