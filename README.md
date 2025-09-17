# Home-Automation-System

## Description
A simple IoT-based home automation system that allows controlling lights and fans via a web dashboard using ESP32 and Relay Modules.

## Features
- Control multiple devices remotely via web dashboard
- Real-time device status updates
- Easy setup for home automation demo

## Hardware Components
- ESP32
- Relay Module
- LEDs / Fan / Light bulbs
- Jumper Wires / Breadboard

## Software
- Arduino IDE (for ESP32)
- Optional React dashboard for control

## Circuit Diagram
<img width="1536" height="1024" alt="circuit-diagram" src="https://github.com/user-attachments/assets/4c4854b0-52f4-41ad-b735-0357f43cea39" />

## 🎞️ Live Demo
https://www.youtube.com/watch?v=4bpU2V0kms8&t=6s


## How to Run
1. Upload `Arduino/home-automation.ino` to ESP32 via Arduino IDE
2. Connect devices as per the circuit diagram
3. Connect ESP32 to Wi-Fi
4. Open React dashboard:
   ```bash
   cd Software/dashboard
   npm install
   npm start
