# Energy-Efficient-Geyser
Energy Efficient Smart Geyser with IR Remote and RTC Scheduling


# 🔥 Energy Efficient Smart Geyser with IR Remote and RTC Scheduling

## 📌 Project Overview

This project presents a **Smart Energy Efficient Geyser System** built using the ESP32 microcontroller.
The system intelligently controls water filling and heating using:

* IR Remote (Manual Mode)
* RTC-Based Timing Control
* Flow Sensor for Water Measurement
* Temperature Monitoring
* Safety Protections

The goal of this project is to reduce electricity wastage, improve safety, and enhance user control.

---

## ⚙️ System Flow

```
Enter Liters
↓
Press ENTER
↓
Solenoid Valve Opens
↓
Flow Sensor Counts Water
↓
Required Liters Reached
↓
Solenoid Valve OFF
↓
Select Heating Mode (Time / Temperature)
↓
Heating Starts
↓
Countdown or Temperature Monitoring
↓
Heating Completed
↓
Buzzer Alert
```

---

## 🚀 Key Features

* IR Remote Based Manual Control
* RTC-Based Accurate Heating Time
* Temperature Mode & Time Mode
* Automatic Water Filling Using Flow Sensor
* Solenoid Valve Control
* Over-Temperature Protection (55°C Hard Cutoff)
* Maximum Runtime Protection
* Dry-Run Protection
* Real-Time LCD Feedback
* Buzzer Alert on Completion
* Active-Low Relay Logic
* Non-Blocking Firmware Design

---

## 🔌 Hardware Components Used

* ESP32 Development Board
* DS18B20 Waterproof Temperature Sensor
* YF-S201 Water Flow Sensor
* DS3231 RTC Module
* 16x2 I2C LCD Display
* IR Receiver Module
* 2-Channel Relay Module
* Solenoid Valve
* Buzzer
* Push Button (LCD Reset)
* AC Bulb (Used for Safe Testing)

---

## 🧠 Safety Features

✔ Over-Temperature Cutoff
✔ Dry-Run Detection
✔ Maximum Continuous Heating Limit
✔ Relay Fail-Safe OFF
✔ Manual Control Lock During Operation

---

## 💡 Energy Efficiency Benefits

* Prevents overheating
* Prevents unnecessary continuous heating
* Stops heating automatically after reaching target
* Avoids dry heating damage
* Measures exact water quantity before heating

This significantly reduces power consumption and increases appliance life.

---

## 🖥️ Software Design

* Embedded C++ (Arduino Framework)
* State Machine Architecture
* Interrupt-Based Flow Counting
* Non-Blocking System Design using millis()
* I2C Communication for LCD & RTC
* Modular Code Structure

---


## 📊 Future Improvements

* IoT-Based Online Monitoring (Blynk Integration)
* Energy Consumption Monitoring
* Mobile App Control
* OTA Firmware Update
* Fault Logging System

---

## 👨‍💻 Developed By

P. Venkata Kishor Kumar Reddy
B.Tech – Embedded Systems

---

## ⭐ If You Found This Useful

* Star this repository
* Fork and improve
* Share your suggestions

---

