# Temperature Sensor Alarm System

A simple embedded system that monitors temperature levels using an LM35 sensor and triggers an alert when the temperature exceeds a safe threshold.

Developed as part of **CSE 210 – Digital Logic Design** course at Imam Abdulrahman Bin Faisal University.

---

## 🎯 Objective
To design a digital system that senses and responds to changes in temperature by activating an alarm signal when critical limits are reached.

---

## ⚙️ Tools and Components
- **Arduino Uno**
- **LM35 Temperature Sensor**
- **Buzzer**
- **LED**
- **Resistors & Jumper Wires**
- **Tinkercad (for simulation)**

---

## 🧠 System Logic
1. The LM35 sensor continuously measures temperature.  
2. Arduino reads the analog data and converts it to Celsius.  
3. If the measured temperature exceeds a predefined threshold:  
   - The **Buzzer** sounds an alarm.  
   - The **LED** lights up as a visual alert.  
4. When the temperature returns to normal, both alarms turn off automatically.

---

## 🔢 Logic Design Summary
| Component | Function |
|------------|-----------|
| LM35 | Converts temperature to voltage signal |
| Arduino | Compares temperature with threshold |
| LED | Visual alert |
| Buzzer | Sound alert |
| Resistors | Limit current for LED and sensor stability |

---

## 🧩 Circuit Workflow
LM35 → Arduino Analog Input → (Condition Check)
If Temp > Threshold → LED ON + Buzzer ON
Else → LED OFF + Buzzer OFF


---

## 🧪 Simulation
The system was implemented and tested using **Tinkercad**.  
Temperature thresholds were adjusted to verify both normal and alert states.  
All connections and logic gates worked as expected.

---

## 💡 Project Goals
- Understand how sensors interact with microcontrollers  
- Implement digital decision-making using conditional logic  
- Enhance circuit simulation and testing skills  

---


## 📎 Notes
This project demonstrates the application of **digital logic and embedded system design** to solve real-world safety problems.  
Simple, effective, and practical — bridging **logic design** with **IoT fundamentals**.

---

✨ *Built with logic, teamwork, and creativity.*




