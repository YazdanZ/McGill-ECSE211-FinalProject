# DPMProject
Final Project in McGill ECSE 211-Design Principles and Methods

## Project Description 
The project consisted of constructing an autonomous Robot performing a search and rescue operation on a stranded vehicle inside of a closed area (Figure 1) while being able to localize, navigate and avoid randomly placed obstacles. The Robot’s software is written in Java, using the LEJOS library that provides support for Mindstorm EV3 hardware such as motors and sensors in a Java development environment. The project involved performing a full engineering process, from project and resource management, to designing, implementing, optimizing and troubleshooting a hardware/software system. 

<p align="center">
  <img src="https://github.com/UNIX-Like-Human/McGill-ECSE211/blob/master/Preview/Competition%20Map.png">
</p>

## Hardware Description 
The robot has an ultrasonic sensor facing forward for ultrasonic localization. A light sensor, placed above the ultrasonic sensor, detects the colour of an object in front of the robot. A light sensor is also mounted next to each of the wheels; these will be used for light localization when travelling throughout the course. The light sensors would recognise when the robot is askew (the sensors detect the course’s lines at different times) and adjust the robot’s trajectory. The rear of the robot has a “claw”, powered by a medium motor, to connect to the trailer. Once the robot sees the trailer, it will adjust itself to the proper distance and rotate 180 degrees before closing the claws and hitching to the trailer.

Front-Side                 |  Back-Side
:-------------------------:|:-------------------------:
![](https://github.com/UNIX-Like-Human/McGill-ECSE211/blob/master/Documentation/Supporting%20Documents/Hardware/Robot%20V%201.1/Renders/Robot%20V1.1%20-%20Front-Side.jpg)   |  ![](https://github.com/UNIX-Like-Human/McGill-ECSE211/blob/master/Documentation/Supporting%20Documents/Hardware/Robot%20V%201.1/Renders/Robot%20V1.1%20-%20Back-Side.jpg)
