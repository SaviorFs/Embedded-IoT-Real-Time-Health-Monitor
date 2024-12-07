# Real-Time Health Monitoring System

## Overview
A portable system to monitor heart rate, SpO2 levels, and temperature in real time. Data is displayed on an OLED screen and can be transmitted via Bluetooth/Wi-Fi.

## Features
- Heart rate and SpO2 monitoring.
- Temperature tracking.
- Real-time data display on OLED.
- Bluetooth/Wi-Fi integration for remote monitoring.

## Components
- ESP32
- MAX30102 (Heart Rate Sensor)
- DS18B20 (Temperature Sensor)
- LiPo Battery (3.7V)
- OLED Display
- TP4056 Charging Module

## Setup
1. Clone this repository.
2. Upload the code to ESP32 using Arduino IDE.
3. Connect the hardware as per the schematic (see `hardware/`).

## To-Do
- [ ] Integrate Bluetooth communication.
- [ ] Add motion tracking.
- [ ] Optimize battery usage.
