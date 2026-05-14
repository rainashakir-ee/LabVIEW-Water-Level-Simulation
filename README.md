# 💧 Water Level Indicator Simulation in LabVIEW

## 📌 Project Overview

This project demonstrates a simple **water level monitoring and control system** built in LabVIEW. It simulates how a tank’s water level can be monitored using thresholds, where indicators (LEDs) respond when the level goes beyond defined limits.

The system helps visualize basic automation logic used in real-world industrial and household water management systems.

---

## ⚙️ Working Principle

The simulation works on simple threshold-based logic:

* If water level goes **below minimum limit**, a LOW indicator turns ON
* If water level goes **above maximum limit**, a HIGH indicator turns ON
* If the level stays within range, both indicators remain OFF

This allows continuous monitoring of safe operating levels in a tank system.

---

## 🧠 Concept Used

This project is built using basic LabVIEW programming concepts:

* While Loop for continuous execution
* Shift Registers for storing previous values
* Comparison functions (Greater than / Less than)
* Boolean LEDs for status indication
* Numeric controls for setting limits

---

## 🖥️ Front Panel (UI)

The front panel includes:

* Tank indicator for water level visualization
* Two vertical sliders for minimum and maximum limits
* LED indicators for LOW and HIGH conditions
* Numeric display for current water level
* Stop button to terminate simulation

---

## 🔧 Block Diagram Logic

The block diagram implements:

* Continuous water level updating using a loop
* Condition checking using comparison blocks
* Automatic indication through LEDs
* Reset/stop control for simulation termination

---

## 📸 Screenshots

(Add your images here)

* Front Panel
* Block Diagram

---

## 🚀 Key Features

* Real-time water level simulation
* Threshold-based alert system
* Simple and clean UI design
* Automatic logic-based control flow

---

## 🎯 Learning Outcome

This project helped in understanding:

* Basic automation systems
* LabVIEW graphical programming
* Real-time monitoring logic
* Practical use of control systems in simulation

---

## 📌 Note

This is a simulation-based project intended for educational purposes. It demonstrates how water level monitoring systems work in real-world applications using LabVIEW.

---
