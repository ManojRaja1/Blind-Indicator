# BLIND INDICATOR
# Overview

The Blind Indicator Using Arduino is a simple yet effective project aimed at helping visually impaired individuals by providing them with an auditory indication of obstacles in their path. The system uses ultrasonic sensors to detect obstacles and Arduino to process the data and trigger a buzzer to alert the user.

# Features

Obstacle Detection: Uses ultrasonic sensors to detect objects within a certain range.
Auditory Alerts: A buzzer provides audio feedback to the user when an obstacle is detected.
Customizable Sensitivity: Adjust the distance at which the sensor triggers the alert.
Portable and Lightweight: Can be easily carried or attached to a walking stick.

# Components

* Arduino Uno: 
The microcontroller that processes sensor data.
* Ultrasonic Sensor (HC-SR04):
Measures the distance to the nearest object.
* Buzzer:
Provides auditory alerts when an obstacle is detected.
* Breadboard and Jumper Wires:
For connecting the components.
* Battery Pack:
Powers the entire system.

# Circuit Components:

* Arduino Uno
* Ultrasonic Sensor (HC-SR04):
* VCC to Arduino 5V
* GND to Arduino GND
* Trig to Arduino Pin 9
* Echo to Arduino Pin 10
* Buzzer:
  
   *Positive (longer leg) to Arduino Pin 8*
  
   *Negative (shorter leg) to Arduino GND*
* Battery Pack (optional):
* Positive to Arduino Vin
* Negative to Arduino GND

***Circuit Diagram***

![Blind_Indicator_Arduino_Circuit_Diagram](https://github.com/user-attachments/assets/f6b15350-f383-4f83-9a42-06d959941f76)

# How It Works

* The ultrasonic sensor continuously measures the distance to objects in front of it.
* When an object comes within the predefined range, the Arduino processes the data and triggers the buzzer.
* The buzzer emits a sound to alert the user of the nearby obstacle.
  
# Installation

* Connect the components according to the circuit diagram provided.
* Upload the provided code to your Arduino board using the Arduino IDE.

# Usage

* Power on the Arduino using a battery pack.
* The system will automatically start detecting obstacles.
* Adjust the sensor range in the code if necessary.

