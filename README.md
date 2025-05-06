# 🚰 AquaGuard: Smart Faucet-Attachable Water Level Controller
“Prevent overflow. Save every drop. Let AquaGuard handle the flow.”

## 🌟 Overview
AquaGuard is a smart, faucet-attachable device that automatically manages your water supply using a digital level sensor and relay-controlled valve. Whether you're filling a drum, a tank, or a container — AquaGuard ensures you never worry about overflows or dry tanks again.

Perfect for homes, urban gardens, and water-conscious users.

## 🧰 Components
Arduino Nano

Digital Water Level Sensor (e.g., float switch)

12V Electric Valve (inline, faucet-compatible)

1-Channel Relay Module

Power Supply (12V for valve, USB/5V for Arduino)

Waterproof Enclosure (optional but recommended)

## 🔧 Setup & Pin Connections
Component	Arduino Nano Pin
Water Level Sensor	D2
Relay Module (IN)	D8

The valve is connected to a faucet using standard threading or adapters, and the relay controls when water flows in or not.

## 🧠 Functionality
Low Water Level Detected: Valve opens, water flows in.

Water Reaches Desired Level: Valve closes, water stops.

Fully Automated: No more checking, switching, or guessing.

## 💡 Highlights
Easy faucet attachment

Prevents overflow and dry fill-ups

Reduces water waste

Ideal for home tanks, rain barrels, or garden containers

## 🔒 Safety & Tips
Use a waterproof casing for electronics

Use opto-isolated relay modules

Ensure secure valve connection to prevent leaks

Power valve with external 12V, not directly from Arduino

## 🚀 Future Upgrades
Wi-Fi/Bluetooth monitoring (e.g., ESP8266)

Mobile app integration

Multi-level sensor logic (min, mid, max)

Solar-powered version
