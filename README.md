# 🚗 Parking Slot Detection System using Arduino

## 📌 Description
This project is a **Parking Slot Detection System** using Arduino and an **Ultrasonic Sensor** to detect the presence of a vehicle. It helps identify whether a parking space is **occupied or available** by measuring the distance between the sensor and the object.

LEDs and a buzzer are used to indicate the parking status, making it easy to understand in real-time.

---

## 🔧 Features
- 🚗 Detects vehicle presence using ultrasonic sensor  
- 📏 Measures distance in real time  
- 🔴 LED indicates parking slot occupied  
- 🟢 LED indicates parking slot available  
- 🔊 Buzzer alert for close distance  
- ⚡ Fast and accurate detection  

---

## 🧰 Components Used
- Arduino Uno  
- Ultrasonic Sensor (HC-SR04)  
- LEDs (Red & Green)  
- Buzzer  
- Resistors  
- Breadboard  
- Jumper Wires  

---

## ⚙️ Working Principle
1. Ultrasonic sensor sends sound waves  
2. Waves reflect back after hitting an object  
3. Arduino calculates the distance  
4. If distance < set threshold (e.g., 10 cm):
   - Red LED ON (Slot Occupied)  
   - Buzzer ON  
5. If distance > threshold:
   - Green LED ON (Slot Available)  

---

## 🔌 Circuit Diagram
<img width="826" height="570" alt="image" src="https://github.com/user-attachments/assets/d7b1aacf-76fc-40ab-9c50-bc6d6af7fe25" />
Downloaded from https://wokwi.com/
Simulate this project on https://wokwi.com

  
