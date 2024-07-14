
### README for hand-gesture-controlled-robot

# Hand-Gesture Controlled Robot

This GitHub repository contains the source code and documentation for a hand-gesture-controlled robot using Arduino. The project aims to create a robot that responds to hand gestures for movement control, designed to assist disabled individuals with ease of operation. The system includes an accelerometer, RF modules, and an ultrasonic sensor for obstacle detection.

## Description

The project utilizes an accelerometer, RF transmitter and receiver, and an ultrasonic sensor to control the robot's movements and detect obstacles.

## Components

- Arduino Uno
- ADXL 335 Accelerometer
- RF Transmitter and Receiver
- Motor Driver
- Ultrasonic Sensor
- Buzzer

## Features

- Gesture-based control for forward, backward, left, right, and stop movements.
- Obstacle detection with alert buzzer.
- Wireless communication between the glove and robot.

## Methodology

1. **Transmitter Section**: The hand glove equipped with an accelerometer and RF transmitter captures hand gestures and transmits the data wirelessly.
2. **Receiver Section**: The RF receiver on the robot receives the data, processes it with the Arduino, and controls the motors accordingly. Ultrasonic sensors detect obstacles and trigger alerts.

## Usage

Upload the transmitter and receiver code to the respective Arduino boards. Assemble the components as per the provided circuit diagrams. Wear the glove to control the robot with hand gestures.
