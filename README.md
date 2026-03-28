# AI Wearable Gas Sensor (ESP32 + TensorFlow Lite)

## Overview
This project is a wearable environmental monitoring device capable of detecting harmful gases and air quality conditions in real time.

The system integrates a gas sensor array, an ESP32 microcontroller, and an AI model deployed using TensorFlow Lite for Microcontrollers.

## Features

- Real-time gas detection
- Edge AI inference
- Cloud data logging
- LCD user interface
- Wireless connectivity

## Hardware Architecture

Components:

ESP32 Microcontroller  
MQ-135 Gas Sensor  
LCD1602 I2C Display  
Power Management Module

## System Architecture

Sensor → ESP32 → AI Model → LCD + Cloud

## AI Model

Framework: TensorFlow  
Deployment: TensorFlow Lite for Microcontrollers

Detected gases include:

- CO2
- CO
- Ammonia
- VOC
- Smoke

## Hardware Setup

Insert picture of:

- Breadboard
- wiring
- PCB (if available)

## Results

Accuracy: ~90% classification accuracy during testing.

## Future Improvements

- Custom PCB
- Additional gas sensors
- Edge ML optimization
