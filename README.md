
![robot design](https://user-images.githubusercontent.com/61570570/134093942-0923308f-a86f-418d-912c-3fbabe3670fa.JPG)
# robiticsproject
DESIGN AND IMPLEMENTATION OF SELF NAVIGATING AUTONOMOUS ROBOT WITH 2D-MAPPING USING ARDUINO

INTRODUCTION
1.1	Introduction
To design a path finding robot with moderate velocity and to map the unknown environment using ARDUINO.  
Ultrasonic sensors (also known as transceivers when they both send and receive, but more generally called transducers) work on a principle similar to radar or sonar which evaluates attributes of a target by interpreting the echoes from radio or sound waves respectively. Ultrasonic sensors generate high frequency sound waves and evaluate the echo which is received back by the sensor. Sensors calculate the time interval between sending the signal and receiving the echo to determine the distance to an object.
The controlling device of the whole system is a Arduino. The Arduino reads the ultrasonic sensors data regarding the obstacle detected. Robot moves in the same direction until it reaches another turn. To perform this intelligent navigation, the Arduino is loaded with an efficient program written using embedded ‘C’ language.
      Here we are using zigbee technology for data communication. The arduino microcontroller continuously monitors the path of vehicle through the ultrasonic sensor and this Information sends to the pc through zigbee technology. Meanwhile the MATLAB code is run in the PC. So we can know the TRAVELED PATH MAP on PC through MATLAB. 
1.2 Project Overview
An embedded system is a combination of software and hardware to perform a dedicated task. Some of the main devices used in embedded products are Microprocessors and Microcontrollers.
Microprocessors are commonly referred to as general purpose processors as they simply accept the inputs, process it and give the output. In contrast, a microcontroller not only accepts the data as inputs but also manipulates it, interfaces the data with various devices, controls the data and thus finally gives the result.
 The project “SELF NAVIGATING AUTONOMOUS ROBOT WITH 2D-MAPPING USING ARDUINO” aims at developing an intelligently navigable Robot using obstacle sensors and Digital compass. And also wireless communication using ZIGBEE technology. To do this particular task using arduino written in embedded c language and PC with MATLAB.
1.3 Aim and objectives
The aim of the project is to design an autonomous robot which navigates itself in an unknown path and gives a 2D map of the path in which it has travelled.
The objectives are
1.	To find path free of obstacles using ultra-sonic sensors.
2.	To find the safest path around with arduino by comparing the outputs of various sensors. 
3.	To transfer the data required to map the surroundings in 2D format by using a Zigbee.
4.	Using MATLAB software to process the data acquired by Zigbee receiver to obtain        the 2D map in pc/laptop.


SOFTWARE DESCRIPTION
This project is implemented using following software’s:
•	Arduino IDE compiler - for navigation part
•	Matlab – for mapping part

