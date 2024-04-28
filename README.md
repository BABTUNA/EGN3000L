# EGN3000L

## Overview
This GitHub repository contains the Arduino code for the line follower robot. For a detailed explanation, refer to the executive summary.

## Components
To run the code, you need:
- Arduino Uno board
- IR sensors
- DC motors
- H-Bridge

## Operation
The line follower robot operates as follows:
1. It moves forward as long as the path is straight.
2. It turns to follow the curve when it detects one using the IR sensors.
3. The robot stops when both IR sensors detect the black tape.

Note: Tests confirm that the robot will follow the tape from any starting orientation.
