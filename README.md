# Autonomous Maze Solver Bot using Arduino  

## Overview  
This project develops an autonomous robot that navigates through a maze without human intervention. Using ultrasonic sensors and motor control, the bot detects obstacles and makes real-time pathfinding decisions. The system is designed for robotics applications, automation projects, and learning about embedded systems.  

## Features  
- Navigate mazes autonomously using sensor-based decision-making.  
- Real-time obstacle detection with ultrasonic sensors.  
- Efficient motor control using an L298N driver module.  
- Simple logic-based pathfinding without external guidance.  
- Adjustable speed and delay parameters for fine-tuning movements.  

## Hardware Components  
- **Microcontroller:** Arduino Uno (or compatible)  
- **Sensors:** HC-SR04 Ultrasonic Sensors (for obstacle detection)  
- **Motor Driver:** L298N Motor Driver Module  
- **Motors:** DC Motors with wheels  
- **Power Source:** Battery pack for portable operation  
- **Chassis:** Custom or pre-built robotic frame  

## Programming Language  
- C++ (Arduino)  

## Libraries  
- Standard Arduino libraries for motor control and ultrasonic sensors  

## Workflow  
1. **Initialization** – Arduino sets up sensor pins, motor driver, and serial communication.  
2. **Data Collection** – Ultrasonic sensors measure distances from nearby obstacles.  
3. **Decision Making** – Pathfinding logic determines the next movement based on sensor input.  
4. **Motor Control** – Commands are sent to the motor driver to execute movements.  
5. **Continuous Looping** – The bot repeats the process until it reaches the exit or a stopping condition.  

## Key Insights  
- The bot can autonomously navigate unknown environments with real-time obstacle detection.  
- Simple logic-based decision-making allows for efficient movement through a maze.  
- Sensor placement and tuning play a crucial role in performance. .
