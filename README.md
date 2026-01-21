# 🏠 Smart Home Automation Using ATmega32
---
##  📌 Project Overview
---
This project implements a smart home automation system using an ATmega32 microcontroller.
The system automatically controls lighting, fan speed, and safety alerts based on environmental conditions.
---
##  🚀 Features
 - 🌡️ Automatic Fan Speed Control
 - Fan speed is adjusted based on temperature measured by LM35 sensor using PWM.
 - 💡 Automatic Lighting Control
 - LEDs indicate ambient light intensity based on LDR readings.
 - 🔥 Fire Detection & Alarm
 - Flame sensor triggers buzzer and critical alert on LCD.
 - 📟 LCD Display
 - Displays temperature, light intensity, fan status, and alerts.
 - 🧩 Layered Architecture
 - Modular drivers for GPIO, ADC, PWM, LCD, sensors, and actuators.

---

##  🧰 Hardware Components
 - ATmega32 Microcontroller (16 MHz)
 - LM35 Temperature Sensor
 - LDR Light Sensor
 - Flame Sensor
 - 16x2 LCD (8-bit mode)
 - DC Motor with H-Bridge
 - LEDs (Red, Green, Blue)
 - Buzzer

---

##  🛠️ Software & Drivers
 - ADC Driver
 - GPIO Driver
 - PWM Driver (Timer0)
 - LCD Driver
 - LM35 Driver
 - LDR Driver
 - DC Motor Driver
 - Flame Sensor Driver
 - Buzzer Driver
