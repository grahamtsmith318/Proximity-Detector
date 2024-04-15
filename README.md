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

## Schematic
![Schematic](https://github.com/grahamtsmith318/Proximity-Detector/assets/161498179/34d964cb-ea53-4bad-9ba6-727e3ec8990e)

## Breadboard Layout
![Breadboard](https://github.com/grahamtsmith318/Proximity-Detector/assets/161498179/b663e5ee-b3c7-49c2-ac11-e9d3bba72684)

## Perfboard
![Full Device](https://github.com/grahamtsmith318/Proximity-Detector/assets/161498179/e8c42b8d-0c80-4c15-a18c-07be3415852a)
![Perfboard Front](https://github.com/grahamtsmith318/Proximity-Detector/assets/161498179/b097f241-8494-4e71-bfb9-f8c50a70011d)
![Perfboard Back](https://github.com/grahamtsmith318/Proximity-Detector/assets/161498179/75de4737-7f15-4bdc-9305-8e0abcad103d)
