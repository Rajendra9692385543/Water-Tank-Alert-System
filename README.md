# 🚰 Water Tank Alert System
A smart IoT-based water level monitoring system built using NodeMCU ESP8266 that detects tank conditions and alerts users to prevent overflow and dry-run situations.

## 📌 Overview
This project monitors the water level in a tank using dual float switches and provides real-time alerts using a buzzer system.

It is designed to be low-cost, reliable, and easily expandable into a fully automated smart water management system.

## ✨ Features
🔔 Overflow Detection Alert

⚠️ Low Water Level Warning

🔊 Buzzer-Based Notification System

🔁 Dual Float Switch Validation

⚡ Low Power & Cost Efficient

🔧 Simple Installation & Maintenance

## 🛠️ Hardware Used
NodeMCU ESP8266

Float Switch Sensors (2x)

Passive Buzzer

Jumper Wires

5V Power Adapter

## ⚙️ Working Principle
The low-level float switch detects when water falls below a minimum threshold.

The high-level float switch detects when the tank is full.

Based on the sensor inputs:

Continuous buzzer → Overflow condition

Intermittent buzzer → Low water level

No sound → Normal state

## 🔌 Pin Configuration


LOW_FLOAT  -> D5  
HIGH_FLOAT -> D6  
BUZZER     -> D7


## 📸 Project Images
(Add your images inside /images folder and link here)

Tank Setup

Sensor Placement

Device Setup

## 🚀 Future Upgrades
This system is designed to evolve into a complete smart water automation solution:

🔌 Automatic Motor ON/OFF System

Motor turns ON when water is low

Motor turns OFF when tank is full

📱 Mobile Control

Manual motor control via mobile app

Real-time alerts and notifications

🌐 Web Dashboard

Monitor tank level remotely

Control motor from browser

View usage data and logs

📡 WiFi-Based Alerts

Push notifications (overflow / low level)

SMS or app alerts

## 📦 Installation
Install Arduino IDE

Add ESP8266 Board Manager

Upload code to NodeMCU

Connect float switches and buzzer

Power the system

## 🎯 Applications
Household water tanks

Apartments & buildings

Shops and small industries

Farms and irrigation systems

## 👨‍💻 Developer Info
Rajendra Das
B.Tech CSE
