# ♻️ Waste Segregation Monitoring System  
*(Metal and Plastic Separation)*

An automated mini project designed to identify and segregate metal and plastic waste using sensor-based detection and Arduino control.

---

## 📌 Project Overview

The Waste Segregation Monitoring System is a conveyor-based automated system developed to separate metallic and non-metallic (plastic) waste materials. The system reduces manual sorting, improves recycling efficiency, and demonstrates the practical application of embedded systems and mechanical design.

The project was developed as **Mini Project – I** under the Department of Mechanical Engineering at **Mepco Schlenk Engineering College, Sivakasi** :contentReference[oaicite:0]{index=0}

---

## 👤 Team Members

- **Deva Vishnu K. S**
- Agilan C. U  
- Seenirajperumal M  

---

## 🎯 Objectives

- Design and fabricate a conveyor-based waste segregation system  
- Detect metallic waste using an inductive proximity sensor  
- Detect non-metallic (plastic) waste using a capacitive proximity sensor  
- Use infrared sensors for confirmation and synchronization  
- Control sorting operations using an Arduino UNO  
- Achieve reliable segregation with laboratory-scale accuracy  

---

## ⚙️ System Description

The system operates on a sequential detection and sorting principle:

1. Waste material is placed on a moving conveyor belt  
2. An **inductive proximity sensor** detects metallic objects  
3. A **capacitive proximity sensor** detects non-metallic objects  
4. **Infrared sensors** confirm the position of the detected material  
5. **Servo motors** actuate sorting flaps to divert waste into separate bins  

All sensors and actuators are controlled using an **Arduino UNO microcontroller** programmed in C.

---

## 🧠 Hardware Components

- Arduino UNO  
- Inductive Proximity Sensor (Metal detection)  
- Capacitive Proximity Sensor (Plastic detection)  
- Infrared Sensors (Path confirmation) - 2 
- Servo Motors (Sorting mechanism) - 2
- 12V DC Geared Motor (Conveyor drive)  
- Conveyor belt with PVC rollers  
- Plywood frame  

---
## Circuit diagram
<img width="2500" height="1345" alt="circuit_image" src="https://github.com/user-attachments/assets/ea1bc3ba-1325-4e82-8875-8350a971b093" />

## 💻 Software & Tools Used

- Arduino IDE (C programming)  
- AutoCAD (2D design)  
- Fusion 360 (3D modeling)  
- SolidWorks (stimulation)  
- ANSYS (Basic analysis)
  
## 3D Modelling
<img width="630" height="452" alt="Screenshot 2025-11-13 213835" src="https://github.com/user-attachments/assets/fc981f7a-b2f6-49d9-9961-9988db1a5531" />

---

## 🔌 Working Principle

Metallic waste generates eddy currents when passing near the inductive sensor, triggering a digital signal.  
Non-metallic waste alters the dielectric field of the capacitive sensor, indicating plastic material.  
Once detection is confirmed by IR sensors, the corresponding servo motor diverts the waste into the assigned collection bin.

Materials not detected are sent to a default bin.

---

## 📊 Results

- Metal detection accuracy: **~86%**  
- Non-metal detection accuracy: **~76%**  
- Overall system accuracy: **~80%**  
- Throughput: **600–800 items/hour (lab conditions)**  

These results validate the feasibility of automated waste segregation at a prototype level:contentReference[oaicite:1]{index=1}

---

## ⚠️ Limitations

- Detects only one object per cycle  
- Limited detection for very small or thin materials  
- Manual conveyor activation  
- Binary classification only (metal vs non-metal)  

---

## 🚀 Future Improvements

- Automatic conveyor control  
- Improved sensor sensitivity  
- Multi-category waste segregation  
- IoT-based monitoring and data logging  
- Industrial-scale design optimization  

---

## 📘 Conclusion

This mini project successfully demonstrates a low-cost, sensor-based waste segregation system integrating mechanical design, embedded systems, and real-time control logic. It serves as a strong educational model for automation in sustainable waste management.

---

## 📎 Reference

Project documentation and performance data are based on the official Mini Project report submitted to Mepco Schlenk Engineering College, Sivakasi.
