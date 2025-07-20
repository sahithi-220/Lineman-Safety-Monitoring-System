# ⚡ Lineman Safety Monitoring System

An embedded safety solution using Arduino to protect electrical line workers (linemen) from accidental exposure to live wires during maintenance operations. It includes real-time voltage detection, buzzer alerts, and optional GSM-based emergency notifications.

---

## 🛠️ Built With

- **Microcontroller:** Arduino
- **Sensors:** Voltage Detection Sensors
- **Modules:** GSM Module (SIM800/900), Buzzer, LED indicators
- **Programming Language:** Embedded C / Arduino IDE

---

## 📝 Project Description

The **Lineman Safety Monitoring System** is designed to detect high voltage on electrical lines before linemen begin work. By alerting them with audio-visual indicators and optionally sending emergency alerts via GSM, this system aims to reduce risk and improve field safety during electrical maintenance tasks.

---

## ✅ Key Features

- 🔋 **Live Wire Detection**  
  Voltage sensors detect the presence of current in lines and alert the lineman accordingly.

- 🚨 **Emergency Alert System**  
  If unsafe conditions are detected (e.g., live wire contact), the system triggers a buzzer and optionally sends an SMS using a GSM module.

- 📳 **Real-Time Alerts**  
  Combines buzzer sounds and LED indicators for immediate feedback.

- 🔒 **Safety-First Approach**  
  Prevents the lineman from accidentally interacting with energized lines.

- 📲 **Optional GSM Integration**  
  Sends alerts to supervisors or emergency responders when unsafe voltage is detected.

- 🧠 **Arduino-Controlled Logic**  
  Efficient and reliable embedded system programming ensures responsive monitoring.

---

## 📂 Example Use Case

A lineman preparing to service a transformer connects the safety system. Upon detecting high voltage on the line, the buzzer sounds and a red LED turns on. After confirming the line is de-energized, the system switches to a green LED, signaling safe conditions. If the line becomes unexpectedly live during repair, an SMS alert is automatically sent to the maintenance supervisor.

---

## 🔮 Future Enhancements

- 📍 **GPS Tracking**  
  Pinpoint lineman location in emergency alerts.

- 📡 **LoRa/Wi-Fi Dashboard**  
  Real-time monitoring and incident dashboards.

- 🤕 **Fall Detection Sensor**  
  Trigger alerts if the lineman falls or collapses.

- ☀️ **Solar-Powered Module**  
  Make the system self-sustainable for field deployment.

- 📊 **Incident Logging**  
  Record high voltage events for safety auditing and analytics.

---

## ▶️ Getting Started

### 📌 Prerequisites

- Arduino UNO / Mega
- Voltage Detection Sensors
- GSM Module (e.g., SIM800L)
- Buzzer
- LEDs (Red and Green)
- SIM card (for SMS functionality)
