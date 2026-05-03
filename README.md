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
