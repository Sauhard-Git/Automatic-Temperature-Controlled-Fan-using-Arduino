<div align="center">

# 🌡️ Automatic Temperature Controlled Fan

### *Arduino-Based Smart Cooling System using DHT11 & PWM Control*

![Arduino](https://img.shields.io/badge/Arduino-Uno-00979D?style=for-the-badge)
![Embedded](https://img.shields.io/badge/Embedded-Systems-blue?style=for-the-badge)
![Automation](https://img.shields.io/badge/Project-Automation-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

# 📖 Overview

The **Automatic Temperature Controlled Fan** is an Arduino-based smart cooling system that automatically adjusts the speed of a DC fan according to the surrounding temperature.

The system continuously monitors temperature using a **DHT11 Temperature Sensor** and controls the fan speed using **PWM (Pulse Width Modulation)** through an **L298N Motor Driver**. A **16×2 LCD Display** provides real-time information about the current temperature and motor speed.

This project demonstrates sensor interfacing, PWM motor control, real-time monitoring, and embedded automation using Arduino.

---

# ✨ Features

- 🌡️ Real-Time Temperature Monitoring
- 🌬️ Automatic Fan Speed Control
- ⚡ PWM-Based Motor Speed Regulation
- 📟 Live Temperature Display on LCD
- 🚀 Multiple Speed Levels (Low, Medium, High, Max)
- 🔋 Energy-Efficient Cooling
- 🛠 Beginner-Friendly Arduino Project

---

# 🛠 Components Used

| Component | Quantity |
|-----------|:--------:|
| Arduino Uno | 1 |
| DHT11 Temperature Sensor | 1 |
| L298N Motor Driver | 1 |
| DC Motor/Fan | 1 |
| 16×2 LCD with I2C Module | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |
| External Power Supply | 1 |

---

# ⚙️ Working Principle

```text
System Starts
      │
      ▼
Arduino Initializes
      │
      ▼
Read Temperature from DHT11
      │
      ▼
Compare Temperature
      │
      ▼
Adjust Fan Speed using PWM
      │
      ▼
Display Temperature & Speed on LCD
      │
      ▼
Repeat Continuously
```

---

# 💻 Software Used

- Arduino IDE

---

# 📚 Libraries Used

```cpp
#include <Adafruit_Sensor.h>
#include <DHT.h>
#include <DHT_U.h>
#include <Wire.h>
#include <LiquidCrystal_I2C.h>
```

---

# 🚀 Future Improvements

- 📲 IoT Monitoring using ESP8266
- 📱 Mobile App Control
- ☁️ Cloud Data Logging
- 🌡️ Temperature Graph Visualization
- 🔔 Overheat Alert System
- 🤖 AI-Based Smart Cooling

---

# 🎓 Learning Outcomes

- Arduino Programming
- PWM Motor Control
- DHT11 Sensor Interfacing
- LCD Display Programming
- L298N Motor Driver Control
- Embedded Systems Development

---

# 📸 Project Preview

### 📷 Hardware Setup

<img width="1280" height="960" alt="SETUP OF AUTOMATIC TEMPERATURE FAN" src="https://github.com/user-attachments/assets/b644e9cb-256c-473d-ae09-0a81182aeda7" />

---

### 📷 Circuit

<img width="1280" height="960" alt="CIRCUIT" src="https://github.com/user-attachments/assets/e27c6fc8-80ca-46fb-94dd-ce78adcd89b9" />

---

### 🎥 Demo Video

https://github.com/user-attachments/assets/39dfad40-fc48-41e6-a31d-d4d6c5517d05

---

# 🤝 Contributing

Contributions are welcome!

⭐ Star this repository

🍴 Fork the repository

🔧 Create a new branch

🚀 Submit a Pull Request

---

# 👨‍💻 Author

## Sauhard Agnihotri

Electronics & Communication Engineering Student

### Interests

- Embedded Systems
- Arduino
- IoT
- Automation
- Robotics
- Electronics

---

# ⭐ Show Your Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

<div align="center">

## ❤️ Thanks for Visiting!

If you like this project, don't forget to leave a ⭐ on GitHub!

</div>
