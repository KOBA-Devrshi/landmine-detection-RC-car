# landmine-detection-RC-car
# 🚀 Bluetooth-Controlled Landmine Detection Robot

A smart robotic system designed to simulate safe detection of buried metallic threats using ESP32 and BLE control.

## 🔧 Features
- 📱 BLE-based remote control
- ⚡ Dead-man control (auto stop)
- 🎮 Smooth acceleration using PWM
- 🧲 Metal detection with real-time alert
- 🔋 Dual power architecture

## 🧠 Tech Stack
ESP32, BLE, L298N Motor Driver, Embedded C++, PWM, Robotics

## ⚙️ How it Works
User sends commands via BLE → ESP32 processes → Motor driver controls movement → Metal detector alerts on detection.

## 🔌 Circuit Diagram
![Circuit](circuit/circuit_diagram.png)

## 📸 Project Images
![Robot](images/robot.jpg)

## 📂 Code
Check `/code/esp32_ble_robot.ino`

## 🚀 Future Improvements
- Autonomous navigation
- Sensor fusion
- Camera integration

## 🎯 Applications
- Defence robotics
- Hazardous environment inspection
- Disaster response systems
