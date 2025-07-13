# 🔥 Fire Detection System Simulation (Arduino Project)
📌 Overview
This project simulates a basic fire detection system using an Arduino UNO, a temperature sensor (LM35), and a gas sensor (MQ-2). It is designed to monitor temperature and gas levels in the surrounding environment. When either parameter crosses a critical threshold, the system alerts users via a buzzer (piezo) and an LED indicator.

## ⚙️ Components Used
- 🟦 Arduino UNO

- 🌡️ LM35 Temperature Sensor

- 🛢️ MQ-2 Gas Sensor

- 🔴 LED (Fire indicator)

- 🔊 Piezo Buzzer (Alarm)

- ⚡ 10kΩ Resistor (for analog signal stability)

- 🧪 Breadboard and Jumper Wires

## 🧠 Working Principle
- Temperature Monitoring:
The LM35 sensor reads the surrounding temperature. If it exceeds 80°C, the LED lights up as a visual alert.

- Gas Detection:
The MQ-2 gas sensor continuously checks for the presence of gases like LPG, propane, and methane. If the gas level exceeds a defined threshold (≥ 700), the buzzer is activated as an audible alarm.

- Serial Output:
The system prints both temperature and gas values on the Serial Monitor for real-time monitoring and debugging.

## 💻 Code Location
🔸 The code for this simulation is available in the file: `Fire_Detection_System.ino`

## 📷 Circuit Diagram
<img width="1338" height="649" alt="Fire Detection System" src="https://github.com/user-attachments/assets/4772f9b8-125e-46f9-9029-931d9a460f20" />



