# Differential Drive Line Tracking Robot
## Project Overview
This project involves a differential drive line tracking robot equipped with an array of 8 analog infrared sensors to follow a path made of white tape on a black canvas. Additionally, the robot features a robotic arm capable of picking up items along the path.

## Hardware
Differential drive system
8 analog infrared sensors
Robotic arm

## Software
Firmware written in C

## Features
Line tracking using 8 analog IR sensors
Item pickup with a robotic arm

## Setup Instructions
Clone the repository:
bash
Copy code
```
git clone https://github.com/Ngigi33/LINE_TRACKER_VERSION_2_CODE.git
```

Navigate to the project directory:
bash
Copy code

```
cd LINE_TRACKER_VERSION_2_CODE/Core/Src
```
Compile and upload the firmware:
Use your STM32CubeIDE  to compile and upload the main.c code to your microcontroller.

Results
![PCB](https://github.com/user-attachments/assets/f187b219-7d94-41f7-9089-ca78bb42bbde)


https://github.com/user-attachments/assets/b53a48d4-5031-4ccc-87c7-1ed0910f72ea



## Code Summary
The main.c file initializes the hardware components, including the ADC, DMA, and GPIO, and contains the main loop for line tracking and item pickup. The system uses ADC for reading sensor values, and the robotic arm's control logic is integrated into the main program loop.

## Usage
Place the robot on the path with white tape on a black canvas.
The robot will automatically follow the line and use its robotic arm to pick up items placed along the path.
