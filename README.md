#Hand-Following Car using Arduino and Ultrasonic Sensors:-

This project demonstrates the implementation of a hand-following car using Arduino and Ultrasonic Sensors. The car is designed to follow the movement of a user's hand, maintaining a certain distance using real-time data from the sensors. It serves as a practical exploration of robotics, sensor technology, and embedded systems.

Features:

Real-time hand tracking: The car follows the user's hand based on distance calculations using ultrasonic sensors.

Dynamic obstacle avoidance: If an object other than the hand is detected, the car will stop or adjust its path to avoid collisions.

Configurable sensitivity: Users can adjust the sensitivity of the ultrasonic sensors to control the response distance of the car.

Efficient motor control: The car's motors are controlled through an H-bridge motor driver, ensuring smooth forward and backward motion.

Components:
Arduino Uno – The microcontroller used to process sensor data and control the car’s movement.

Ultrasonic Sensors (HC-SR04) – Two ultrasonic sensors are used to measure the distance between the car and the user's hand.

Motor Driver (L298N) – Used to control the car's motors for movement.

DC Motors – Four motors attached to the wheels to drive the car forward and backward.

Power Supply – Battery pack to power the motors and Arduino.

Circuit Diagram:

The project includes a detailed circuit diagram for connecting the ultrasonic sensors, motor driver, and motors to the Arduino.

Code Structure:

The code is organized into different modules to enhance readability and functionality:

Sensor Module: Handles ultrasonic sensor readings and calculates distance.

Motor Control Module: Controls the car's movement based on sensor input.

Main Control Logic: Integrates sensor data and motor control, ensuring the car follows the user's hand and avoids obstacles.

Key Functions:

getDistance(): Reads data from the ultrasonic sensors and returns the measured distance.

moveForward(): Moves the car forward based on the proximity of the hand.

moveBackward(): Moves the car backward if the hand gets too close.

stopCar(): Stops the car if no hand is detected or an obstacle is too close.

How to Use:

Hardware Setup: Assemble the car with the ultrasonic sensors, motor driver, and Arduino as per the provided circuit diagram.

Upload Code: Upload the provided code to your Arduino using the Arduino IDE.

Power the System: Attach the battery pack and test the car’s movement by placing your hand in front of the sensors.

Future Improvements:

Integrate Bluetooth or IR sensors for remote control functionality.

Improve sensor accuracy for better hand-following performance.

Add a feature for speed control based on hand movement speed.
