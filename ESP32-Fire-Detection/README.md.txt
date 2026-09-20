# ESP32 Fire Detection System

## Overview

The ESP32 Fire Detection System is an IoT-based safety project designed to detect the presence of fire using a flame sensor.

When a flame is detected, the ESP32 activates a buzzer and LED to provide an alert. The sensor readings can also be monitored through the Serial Monitor.

## Objectives

- Detect fire using a flame sensor.
- Process the sensor signal using ESP32.
- Provide an alert using a buzzer.
- Indicate fire detection using an LED.
- Demonstrate a simple IoT-based safety application.

## Components Required

- ESP32 development board
- Flame sensor
- Buzzer
- LED
- Resistor
- Jumper wires
- Breadboard
- USB cable
- Arduino IDE

## Circuit Connections

| Component | ESP32 Pin |
|-----------|-----------|
| Flame Sensor Analog Output | GPIO 34 |
| Buzzer | GPIO 25 |
| LED | GPIO 2 |
| GND | GND |
| VCC | 3.3V/5V according to sensor specification |

## Working Principle

1. The flame sensor detects infrared radiation produced by a flame.
2. The sensor sends an analog signal to the ESP32.
3. ESP32 reads the sensor value through GPIO 34.
4. The reading is compared with a predefined threshold.
5. If a fire condition is detected, the buzzer and LED are switched ON.
6. If no fire is detected, the buzzer and LED remain OFF.
7. The sensor value and detection status are displayed in the Serial Monitor.

## Software

- Arduino IDE
- ESP32 Board Package
- Embedded C/C++

## Source Code

The main program is available in:

`fire_detection.ino`

## Applications

- Fire safety systems
- Small-scale safety monitoring
- IoT-based security systems
- Educational embedded systems projects
- Laboratory fire detection demonstrations

## Advantages

- Simple implementation
- Low-cost components
- Fast fire detection
- Easy to modify
- Suitable for IoT and embedded systems learning

## Future Improvements

The system can be improved by adding:

- Gas/smoke sensors
- Temperature sensors
- Wi-Fi notifications
- Mobile application monitoring
- Cloud data logging
- Automatic water-sprinkler control

## Project Structure

```text
ESP32-Fire-Detection/
│
├── README.md
├── fire_detection.ino
└── circuit_diagram.png

Conclusion
The ESP32 Fire Detection System demonstrates how a microcontroller can be used with a flame sensor to detect fire conditions and generate an immediate local alert. The project provides a basic foundation for developing more advanced IoT-based fire safety systems.