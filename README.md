# Single-axis PID Controller Using Arduino

A practical single-axis PID stabilization project built with **Arduino** and an **MPU6050 gyroscope/accelerometer**.  
The system reads real-time orientation data from the IMU and automatically adjusts motor output to maintain balance when external disturbance is applied.

This project was developed as an end-semester control systems project to demonstrate the real-world implementation of **feedback control**, **sensor fusion**, and **PID-based stabilization**.

---

## Project Overview

The goal of this project is to stabilize a drone on a **single axis** using a PID controller.  
The Arduino reads motion data from the MPU6050 sensor, estimates the angle, computes the control error, and updates the motor PWM signals accordingly.

The repository includes:

- **Arduino implementation** of the PID controller
- **Simulink model** for simulation and analysis
- **Project report**
- **Presentation slides**
- **Demo video**

---

## Features

- Single-axis balance control
- PID-based real-time correction
- MPU6050 sensor integration
- Complementary filtering using accelerometer and gyroscope data
- PWM motor control through Arduino
- Simulink model for system simulation

---

## Repository Structure

```text
Single-axis-PID-Controller-Using-Arduino/
│
├── PID_Drone_Controller.ino              # Arduino source code
├── PID_Drone_Controller_Simulink.slx     # Simulink model
├── LCS_project_report.pdf                # Project report
├── LCS_PRES.pptx                         # Presentation slides
├── DEMO.mp4                              # Demonstration video
└── README.md                             # Project documentation
