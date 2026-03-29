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

** Final Product:
![Final Product](https://github.com/user-attachments/assets/83829fc0-1215-4e8a-97bc-a00bd356a572)


** Web Dashboard:
![Web Dashboard](https://github.com/user-attachments/assets/a4cb63b5-d3bb-4c0b-836e-4ab0b0b3cc0d)


** Prototype:

![Final Product](https://github.com/user-attachments/assets/1f3af6a2-8af9-4885-ab30-001139322c9c)

** Wiring:

https://github.com/user-attachments/assets/ce79b2cf-7276-4e5c-ad13-fc171e988f3f


** Breadboard Setup:
https://github.com/user-attachments/assets/4f72b7c3-d1dd-41ba-8f88-894bfcafdf35



** FPGA board and other components:

-ESP32: https://www.aliexpress.us/item/3256806781289367.html?spm=a2g0o.order_list.order_list_main.376.52f918020sosSj&gatewayAdapt=glo2usa

-MQ 135, MQ 2, MQ 7: https://www.aliexpress.us/item/3256806866518097.html?spm=a2g0o.order_list.order_list_main.381.52f918020sosSj&gatewayAdapt=glo2usa

-Buzzer: https://www.aliexpress.us/item/3256807353554212.html?spm=a2g0o.order_list.order_list_main.371.52f918020sosSj&gatewayAdapt=glo2usa

-SD cards: https://www.aliexpress.us/item/3256806988148676.html?spm=a2g0o.order_list.order_list_main.131.52f918020sosSj&gatewayAdapt=glo2usa

-SD Card Module: https://www.aliexpress.us/item/3256805404831097.html?spm=a2g0o.order_list.order_list_main.146.52f918020sosSj&gatewayAdapt=glo2usa

-Intake Fan: https://www.aliexpress.us/item/3256806997154044.html?spm=a2g0o.order_list.order_list_main.29.52f918020sosSj&gatewayAdapt=glo2usa

-LCD Module: https://www.aliexpress.us/item/3256805831794547.html?spm=a2g0o.productlist.main.65.675d4ccdfBrKiY&algo_pvid=b2222747-6341-4800-9ad1-c4b0692ce3fe&algo_exp_id=b2222747-6341-4800-9ad1-c4b0692ce3fe-32&pdp_ext_f=%7B%22order%22%3A%221336%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%211.41%210.83%21%21%2110.15%215.99%21%402101d9ee17403640911068497e6477%2112000035375219604%21sea%21US%216106863328%21X&curPageLogUid=m0nR93rCEmZN&utparam-url=scene%3Asearch%7Cquery_from%3A


## Results

Accuracy: ~90% classification accuracy during testing.

## Future Improvements

- Custom PCB
- Additional gas sensors
- Edge ML optimization
