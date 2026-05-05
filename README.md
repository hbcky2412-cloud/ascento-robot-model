# ascento-robot-model
Modeling and dynamic analysis of the ASCENTO wheeled-biped robot, including kinematics, floating-base dynamics, closed-loop constraints and contact modeling.
## 🔗 Demo 
👉 [Watch GeoGebra here](https://hbcky2412-cloud.github.io/ascento-robot-model/)
# ASCENTO Robot Modeling

This project focuses on the mathematical modeling and dynamic analysis of the **ASCENTO robot**, a wheeled-bipedal mobile robot capable of balancing and jumping.

The objective of this work is to develop a **complete mathematical model** of the robot in order to support future research in **model-based control methods**.


---

# Overview

ASCENTO is a hybrid mobile robot developed at ETH Zürich.  
It combines **two wheels and articulated legs**, allowing it to move quickly on flat terrain while also being able to jump and overcome obstacles.

Because of this hybrid design, the robot presents several modeling challenges:

- Floating base dynamics
- Closed-loop mechanisms
- Contact constraints with the ground
- Whole-body dynamics

This project studies these aspects and derives the **equations of motion (EoM)** for the robot.

---

# Objectives

The main goals of this project are:

- Study the theoretical background of robot kinematics and dynamics
- Build the kinematic model of the ASCENTO robot
- Derive the dynamic model of the system
- Consider floating-base and contact constraints
- Validate the model using MATLAB computations

The project focuses only on **mathematical modeling**, not hardware implementation or controller deployment.

---

# Methodology

The modeling process follows several steps:

1. Define coordinate frames and system conventions
2. Build the kinematic chain using Denavit–Hartenberg parameters
3. Derive open-loop dynamics
4. Incorporate closed-loop constraints
5. Model contact constraints between the wheels and the ground
6. Obtain the full equations of motion

The dynamic model is derived using:

- Newton–Euler formulation
- Analytical kinematics
- Matrix-based representation of dynamics

---


