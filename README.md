# IntelliPark System 📡

> **Mini Project (22ECE56)**  
> Department of Electronics and Communication Engineering  
> Global Academy of Technology, Bengaluru  
> **Academic Year: 2024-25**  
> Guided by: *Dr. Shantala*

---

## 📘 Introduction

The **IntelliPark System** is a sensor-based embedded system designed to demonstrate real-time monitoring using IR and ultrasonic sensors. The system is managed via a microcontroller and provides real-time updates on a compact OLED display, ensuring responsiveness, user interaction, and reliable operation.

---

## 📚 Literature Survey

Previous works in embedded sensor systems have focused on detection, real-time feedback, and automation in isolated contexts. IntelliPark expands on these ideas by integrating:

- Real-time monitoring and feedback  
- Embedded system and sensor fusion  
- Compatibility with multi-zone environments  
- Enhanced display interface via OLED

---

## ❓ Problem Statement

Conventional sensor-based systems often suffer from delays, limited interfacing, and low integration with real-time feedback mechanisms. There is a growing need for compact, efficient, and intelligent embedded solutions for monitoring and control applications.

---

## 🎯 Objectives

- Demonstrate automation using IR and ultrasonic sensors  
- Deliver real-time system feedback  
- Maximize system responsiveness  
- Ensure low power and high efficiency  
- Use intuitive visual feedback for user clarity  
- Build a modular and scalable embedded platform

---

## ⚙️ Methodology

1. **System Design** – Sensor placement and logical layout  
2. **Hardware Setup** – IR sensors, ultrasonic modules, OLED interfacing  
3. **Embedded Programming** – Microcontroller logic and sensor fusion  
4. **Simulation & Prototyping** – Virtual simulations and physical setup  
5. **Testing & Validation** – Real-world functionality testing  
6. **Optimization & Deployment** – Code refinement and system tuning  

---

## 🧩 Components Used

- Arduino Nano  
- IR Sensors  
- Ultrasonic Sensors (HC-SR04)  
- 16x2 LCD and 1" OLED Display  
- Sealed Lead Battery  
- Jumper Wires  

---

## 🔄 Algorithm (Flow Overview)

```text
1. Initialize system components  
2. Continuously read sensor inputs  
3. Process sensor data for decision making  
4. Display results on OLED display  
5. Repeat monitoring loop
