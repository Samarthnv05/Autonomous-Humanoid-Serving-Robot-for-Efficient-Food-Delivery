# Autonomous Humanoid Serving Robot for Efficient Food Delivery 🤖🍽️

This project presents the design and development of an **autonomous humanoid serving robot** intended for efficient indoor food delivery in restaurant and hospitality environments. The robot combines **humanoid locomotion, embedded control, sensor-based navigation, and human–robot interaction** to automate repetitive serving tasks while maintaining smooth and safe operation.

---

## 📌 Project Overview

The robot is designed as a **compact humanoid platform** with servo-driven legs and arms, capable of carrying food trays and interacting with users. It operates in **two distinct modes**, controlled and monitored through a **web-based dashboard**.

---

## ⚙️ Operating Modes

### 1️⃣ Serving Mode
- Autonomous food delivery using predefined timed-map navigation  
- IMU-based balance control for stable humanoid movement  
- Obstacle detection using ultrasonic and ToF sensors  
- Tray-load monitoring to ensure safe delivery  

### 2️⃣ Q/A Mode
- Voice-based customer interaction  
- Dashboard-managed question–answer database  
- Expressive OLED eye animations for better human–robot communication  

---

## 🧠 System Architecture

- **Controller:** ESP32 microcontroller  
- **Motion System:** Servo-driven humanoid legs and tray-holding arms  
- **Sensors:**  
  - IMU for balance and orientation  
  - Ultrasonic & ToF sensors for obstacle detection  
  - Load monitoring for tray safety  
- **Interaction:**  
  - OLED display for expressive eyes  
  - Speaker for voice output  
- **Control Interface:** Web-based dashboard for monitoring, control, and mode switching  

---

## 🛠️ Hardware Components

- ESP32 Microcontroller  
- High-torque Servo Motors  
- IMU (MPU series)  
- Ultrasonic & ToF Sensors  
- 0.96” OLED Display  
- Li-ion Battery with power management  
- Speaker with audio amplifier  

---

## 💻 Software & Tools

- Embedded C (Arduino IDE)  
- Sensor and servo control libraries  
- Web Dashboard (HTML, CSS, JavaScript)  

---

## 📊 Performance Results

| Parameter | Result |
|---------|-------|
| Path Deviation | 3–5 cm |
| Obstacle Detection Accuracy | ~73% |
| Load Capacity | ~0.5kg |
| Battery Backup | 1–2 hours |
| Dashboard Latency | ~100–150 ms |

These results demonstrate reliable operation for controlled indoor service environments.

---

## 🎯 Applications

- Restaurants and Cafés  
- Hotels and Hospitality Services  
- Hospitals (contactless delivery)  
- Educational and Research Demonstrations  

---

## 🚀 Future Enhancements

- Adaptive navigation for dynamic environments  
- Advanced voice recognition and NLP  
- Improved battery management and endurance  
- Increased load capacity  
- Learning-based behavior adaptation  

---

## 👥 Team

- **Samarth N Vernekar** – Embedded Systems & System Integration  
- Team Members  

---

## 📄 License

This project is intended for **academic and educational purposes**.
