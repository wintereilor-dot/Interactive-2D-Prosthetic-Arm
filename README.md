# Interactive 2D Prosthetic Arm

**Author:** Karla Winter Eilor, Mechanical Enginnering Student  
**Portfolio Project 1**

---

## Purpose

This project is an **interactive 2D simulation of a prosthetic arm** built in MATLAB. It demonstrates the kinematics of a two-segment arm (shoulder + elbow) and allows the user to control joint angles in real time.  

The simulation is useful for:

- Exploring prosthetic arm motion
- Understanding forward kinematics
- Visualizing hand trajectories
- Building a portfolio of biomedical engineering projects

---

## Features

- **Interactive sliders:** Adjust the shoulder and elbow angles in real time.  
- **Click-to-reach:** Click on a target point in the workspace, and the arm will calculate the joint angles to reach that point using inverse kinematics.  
- **Trajectory plotting:** The hand’s movement path is continuously tracked and displayed.  
- **Real-time animation:** Visualizes arm segments, joints, and hand movement dynamically.

---

## How It Works

- The arm is modeled as **two rigid segments**:
  - `L1` = upper arm length
  - `L2` = forearm length
- Forward kinematics is used to compute elbow and hand positions from shoulder and elbow angles.  
- Inverse kinematics computes joint angles when clicking on a target within reach.  
- MATLAB graphics and `uicontrol` sliders provide interactive visualization.

---

## Tools
- MATLAB – main programming environment
- Uicontrol – for interactive sliders
- Plot & scatter functions – for visualizing arm segments, joints, and hand trajectory
- Forward and inverse kinematics algorithms – for computing joint positions and angles

## Getting Started

1. Clone or download this repository.  
2. Open MATLAB and navigate to the project folder.  
3. Run the function:

```matlab
interactiveProstheticArm

