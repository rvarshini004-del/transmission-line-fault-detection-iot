# IoT-Based Overhead Transmission Line Monitoring and Fault Detection

## Project Overview
This project focuses on monitoring overhead transmission lines using an ESP32-based IoT system and a multi-sensor network. It detects abnormal electrical conditions and mechanical changes and provides alerts to improve transmission line safety and reliability.

## Hardware Components
- ESP32 Microcontroller
- Voltage Sensor (0–25V)
- ACS712 Current Sensors
- DHT11 Temperature and Humidity Sensor
- MPU6050 Accelerometer and Gyroscope
- Relay Module
- GSM Module
- ESP32-CAM
- I2C LCD Display
- Buzzer

## Key Features
- Real-time voltage and current monitoring
- Overcurrent and undervoltage detection
- Temperature and humidity monitoring
- Transmission line tilt and movement monitoring
- Fault alerts using GSM
- Live visual monitoring using ESP32-CAM
- IoT data monitoring through ThingSpeak
- Relay-based load disconnection during detected faults

## ThingSpeak Monitoring
The system monitors the following parameters:

1. Generation-side voltage (V1)
2. Distribution-side voltage (V2)
3. Generation-side current (C1)
4. Distribution-side current (C2)
5. Temperature
6. Humidity
7. MPU6050 X-axis
8. MPU6050 Y-axis

## Software Requirements
- Arduino IDE
- ESP32 Board Package
- Required sensor libraries
- ThingSpeak Account

## Project Structure
```text
Transmission-Line-Fault-Detection/
├── README.md
├── ESP32_Main/
│   └── ESP32_Main.ino
├── ESP32_CAM/
│   └── ESP32_CAM.ino
├── ThingSpeak/
│   └── ThingSpeak_Setup.md
└── Circuit_Diagram/
```

## Safety Notice
Use properly isolated voltage-sensing circuits and suitable electrical protection. Never connect high-voltage AC lines directly to the ESP32 or sensor modules.

## Project Status
Source code and implementation files will be added to this repository.
