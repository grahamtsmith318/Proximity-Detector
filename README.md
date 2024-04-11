# Proximity Detector
This repository contains the code for a simple proximity detector. Included in this readme file are diagrams and images of the board.

## Function
The purpose of this device is to detect close objects and alert the user using lights and sound. An ultrasonic sensor detects objects in front of itself. When object comes within a meter of the sensor, the LEDs will light and the buzzer will sound. As the object approaches, more LEDs will light and the pitch of the sound of the buzzer with become higher. Each unlit LED represents 12.5 centimeters of space between the sensor and the approaching object.

## Components
8x LEDs

8x 220 Ohm resistors

1x 74HC595 chip

1x Passive buzzer

1x HC-SR04 ultrasonic sensor

1x Arduino Uno (or comparable board)

1x 9V battery
