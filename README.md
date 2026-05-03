# 🚨 PIR Motion Sensor – Smart Security & IoT Automation
## 📌 Overview
The PIR (Passive Infrared) motion sensor is one of the most commonly used sensors in security and automation systems. It detects motion by sensing changes in infrared radiation emitted by humans, animals, and warm objects.
This repository explains the working principle, hardware behavior, ESP32 interfacing, signal output, and real-world IoT applications of PIR motion sensors.
## 🧠 Working Principle
A PIR sensor does not emit radiation by itself. Instead, it passively detects infrared energy from nearby objects.
When a human body moves across the sensor range, the infrared radiation pattern changes. The sensor detects this variation and generates a digital output signal.
### 🔹 Output Behavior
* HIGH → Motion detected
* LOW → No motion detected
## ⚙️ Internal Structure
A PIR sensor mainly consists of:
Pyroelectric sensing element
* Fresnel lens
* Signal conditioning circuit
* Digital output pin
The Fresnel lens increases the detection area and focuses infrared radiation onto the sensing element.
## 🔌 Pin Configuration
Most PIR sensors have three pins:
* VCC → Power supply
* OUT → Digital signal output
* GND → Ground connection
The OUT pin can be connected directly to a GPIO pin of ESP32 or Arduino.
## 📡 ESP32 Interfacing
The PIR sensor can be connected to ESP32 for IoT-based motion detection.
### 🔹 Basic Flow
* PIR sensor detects motion
* Signal is sent to ESP32 GPIO
* ESP32 processes the input
* Alert or automation action is triggered
## 🌐 IoT Integration
Using ESP32 Wi-Fi capability, PIR sensor data can be sent to cloud platforms or messaging applications.
### 🔹 Example Applications
* Telegram motion alert
* Blynk notification
* Home security system
* Smart lighting automation
## 🧩 Design Considerations
### 🔹 Important Points
* Avoid placing sensor near heat sources
* Adjust sensitivity carefully
* Provide stable power supply
* Test detection range before final installation
## 🚀 Advanced Applications
* Smart home security
* Automatic corridor lighting
* Human presence detection
* Energy-saving automation
* Restricted area monitoring
