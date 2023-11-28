# 🤖 4534 Swerve
Wired wizzards repository for a swerve drive robot.

<div style="display: flex;">
  <img src="./img/img1.gif" style="width: 50%;padding:2px" alt="Image 1">
  <img src="./img/img2.gif" style="width: 50%;padding:2px" alt="Image 2">
</div>
<img src="./img/img3.gif" style="width: 33.33%;padding:2px" alt="Image 2">



<br>

<br>**Table Of Contents:**
- Features
- Hardware
- Source Code

## 📝 Setup


## ✨ Features
Our swerve drive robot has the following features:
- Swerve drive
- Slow roatiational speed for precise turning
- Field centric drive (Via button input)
- Gyro correction
- PID control

## 🔧 Hardware
Our version of the source code has been modified to work with our hardware. 

We use the following hardware for our swerve drive robot:
- 8x [SPARK MAX](https://www.revrobotics.com/rev-11-2158/) motor controllers (Two per module, drive & turn)
- 8x [NEO Brushless](https://www.revrobotics.com/rev-21-1650/) motors (Two per module, drive & turn)
- 4x [CTRE CANcoder](https://store.ctr-electronics.com/cancoder/) (One per module) acts as absolute encoder for the turn motor
- 1x [NavX MXP](https://pdocs.kauailabs.com/navx-mxp/) (One per robot) acts as gyro for the robot to determine heading
- 1x [T.Flight Hotas One](https://www.thrustmaster.com/en-us/products/t-flight-hotas-one/) (One per robot) acts as controller for the driver to control the robot

## ⏳ Source Code
Our swerve drive code is based on a youtube video from [FRC 0 to Autonomous](https://www.youtube.com/watch?v=0Xi9yb1IMyA&t=192s) and their [github repository](https://github.com/SeanSun6814/FRC0ToAutonomous).
    