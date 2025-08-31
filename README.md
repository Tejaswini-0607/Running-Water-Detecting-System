# Running Water Detecting System

An IoT-based project to **monitor running water** using **ESP8266** and **electrodes**.  
This system detects water flow in real-time and sends alerts or logs data for monitoring purposes.

---

## Project Overview
This project uses electrodes connected to an ESP8266 to detect the presence and flow of water.  
It can notify the user via the cloud (e.g., using **IFTTT**) when water is running and log the activity for monitoring purposes.

Key objectives:
- Real-time detection of water flow using electrodes  
- Cloud notifications for monitoring  
- Simple, low-cost IoT water monitoring solution  

---

## Features
- Detect water flow using electrodes  
- Send alerts/notifications through IFTTT or other cloud services  
- Log water usage or activity  
- Lightweight, ESP8266-based solution  

---

## Hardware Requirements
- ESP8266 (NodeMCU or similar)  
- Electrodes for water detection  
- Connecting wires  
- Power supply (5V/3.3V as required)  

---

## Software Requirements
- Arduino IDE   
- ESP8266 board package installed  
- IFTTT account (for notifications)  

---

## Usage
1. Power up the ESP8266.  
2. When water flows and touches the electrodes, it will be detected.  
3. Notifications will be sent via IFTTT if enabled.  
4. Optionally, data can be logged for monitoring purposes.
