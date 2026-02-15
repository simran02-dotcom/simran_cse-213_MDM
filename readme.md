# Traffic Monitoring and Control System Using IoT

## 📄 Research Paper Details

**Title:** Traffic Monitoring and Control System Using IoT  
**Authors:** Ei Swe Zin, Kyaw Zin Latt  
**Journal:** International Journal of Trend in Scientific Research and Development (IJTSRD)  
**Volume:** 3 | Issue: 4 | May-Jun 2019  
**Paper ID:** IJTSRD25138  

---

## 📌 Domain
Internet of Things (IoT)  
Smart Traffic Management System  
Embedded Systems & Web-Based Monitoring  

---

## 📖 Overview of the Research Paper

This research proposes an IoT-based traffic monitoring and control system that helps reduce traffic congestion and waiting time at road intersections.

The system:

- Uses **Ultrasonic Sensors** to detect vehicle presence
- Uses **ESP8266 NodeMCU** to transmit traffic data
- Uses **Arduino UNO** to control traffic lights
- Displays traffic condition on a **web-based IoT platform (Thinger.io)**
- Allows traffic signal timing to be controlled from the website

The system monitors traffic density and adjusts traffic light timing dynamically based on vehicle flow.

---

## 💡 Objective of This Project Implementation

This project recreates the **web-based monitoring and control interface** described in the research paper using:

- HTML
- CSS

The developed web pages simulate:

- Traffic Monitoring Dashboard
- Traffic Density Data Display
- Traffic Light Control Panel
- Status Updates from Sensors

---

## 🖥️ Implemented Web Pages

1. **Dashboard Page**
   - Displays live traffic condition
   - Shows road status (Free / Traffic Jam)
   - Navigation to other modules

2. **Traffic Monitoring Page**
   - Displays vehicle detection status
   - Shows traffic density table
   - Simulates ultrasonic sensor output

3. **Traffic Control Page**
   - Allows changing traffic signal timing
   - Simulates IoT-based signal interruption
   - Represents control section from the paper

---

## ⚙️ Technologies Used

- HTML5
- CSS3
- Basic Web Navigation
- Folder Structuring for Web Projects

---

## 🧠 System Architecture (Based on Paper)

The system is divided into:

### 1️⃣ Monitoring Section
- Ultrasonic Sensor detects vehicles
- NodeMCU sends data to IoT platform
- Website dashboard displays traffic condition

### 2️⃣ Control Section
- Website sends command to NodeMCU
- NodeMCU interrupts Arduino
- Traffic light timing is adjusted dynamically


