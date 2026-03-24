<!-- Logo -->
<p align="center">
  <img src="RadarSystem_Logo.png" alt="Radar System Logo" width="500"/>
</p>

<!-- Title Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%94%B0%20Arduino%20Radar%20System&fontSize=36&width=1200&height=150&color=0:36BCF7,100:0f2027"/>
</p>

<h3 align="center">
  <b style="color:purple;">📡 Arduino-Based Radar System</b>
</h3>

<h3 align="center">
  <b>🔊 Obstacle Detection and Mapping Using Ultrasonic Sensors</b>
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Arduino-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Sensors-Ultrasonic-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Actuator-Servo%20Motor-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Functional-success?style=for-the-badge">
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Overview Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%93%8C%20Overview&fontSize=32&width=1200&height=130&color=0:9D50BB,100:6E48AA" width="100%">

**Arduino Radar System** is an interactive project demonstrating **real-time obstacle detection** and **position mapping** using **ultrasonic sensors mounted on a servo motor**.  

The sensor rotates across 180° to scan the surrounding environment, while Arduino collects distance data and displays it on the **serial monitor** or software like **Processing**.

**Key Highlights:**
- Detects obstacles and measures distances in real-time  
- Servo motor rotates the ultrasonic sensor for scanning  
- Visualizes object positions using serial output or Processing  
- Modular, Arduino-based hardware design for learning  
- Ideal for robotics beginners, hobbyists, and sensor integration projects  

**Keywords:** Arduino radar, obstacle detection, ultrasonic sensor, servo motor, robotics, real-time scanning, distance mapping

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Objectives -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%8E%AF%20Objectives&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

- 🎯 Design and implement a basic radar system using Arduino  
- 🔄 Understand ultrasonic sensor operation for distance measurement  
- 📊 Detect obstacles and map their positions  
- 🤖 Demonstrate actuator control using a servo motor  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Components & Cost -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%92%B0%20Components%20and%20Cost&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

<div align="center">

| Component | Quantity | Approx. Cost (BDT) |
|-----------|---------|------------------|
| Arduino UNO | 1 | 760 |
| Ultrasonic Sensor (HC-SR04) | 1 | 100 |
| Servo Motor | 1 | 130 |
| Jumper Wires | 10 | 25 |
| Breadboard | 1 | 50 |
| USB/Power Supply | 1 | 100 |
| **Total Cost** |  | **1,165+** |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Features -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%9C%A8%20Key%20Features&fontSize=32&width=1200&height=130&color=0:FC5C7D,100:FF416C" width="100%">

- 📡 Real-time obstacle detection  
- 🔊 Measures distances using ultrasonic sensor  
- ⚙ Servo motor rotates sensor for 180° scanning  
- 💡 Serial monitor/Processing visualization of detected objects  
- 🛠 Modular and easy-to-assemble Arduino setup  
- 📚 Educational and robotics-friendly project  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- System Implementation -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=System%20Implementation&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

### 📷 Hardware Setup & Screens
The system integrates Arduino UNO, ultrasonic sensor on a servo motor, and displays distances in real-time.

**Circuit Components:**
- Arduino UNO  
- Ultrasonic Sensor (HC-SR04)  
- Servo Motor (180°)  
- Jumper Wires & Breadboard  
- USB/Power Supply  

**Circuit Diagram:**
<div align="center">
<img src="acircuit_diagram.png" width="500" />
<p><b>Radar System Circuit Diagram</b></p>
</div>

**Operation:**
- Servo rotates ultrasonic sensor across 180°  
- Sensor measures distances to nearby obstacles  
- Data displayed on serial monitor or Processing visualization  

<div align="center">
  <img src="radar_demo.jpg" width="500" />
  <img src="radar_demo1.jpg" width="500" />
  <p><b>Arduino Radar System in Action</b></p>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Project Structure -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%93%82%20Project%20Structure&fontSize=32&width=1200&height=130&color=0:36BCF7,100:0f2027" width="100%">

```bash
Arduino-Radar-System/
│── Arduino_Code/
│ ├── RadarSystem.ino
│ ├── circuit_diagram.png
│ ├── radar_demo.png
│── README.md
```
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Setup & Usage --> <img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%9A%80%20Setup%20&%20Usage&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

Steps to Run:
```bash
1. Connect ultrasonic sensor to Arduino UNO as per the circuit diagram  
2. Mount sensor on servo motor for scanning    
3. Upload RadarSystem.ino to Arduino using Arduino IDE  
4. Power Arduino via USB or external supply  
5. Open serial monitor or Processing to view distance mapping  
6. Observe sensor scanning and distance detection in real-time  
```
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Future Work --> <img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%94%AE%20Future%20Enhancements&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

📡 Add multi-sensor scanning for larger areas   
🤖 Integrate with autonomous robots for obstacle navigation  
💬 Display visualization on external dashboard   
🔋 Optimize power efficiency and add battery monitoring  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 


<!-- Conclusion --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%9C%85%20Conclusion&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

Arduino Radar System demonstrates real-time obstacle detection and distance mapping using ultrasonic sensors and a servo motor.

It serves as an educational project, hobbyist prototype, or basis for more advanced robotic applications.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Author --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%91%A8%E2%80%8D%F0%9F%92%BB%20Author&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

### A. K. M. Masudur Rahman (Gaurab)

🎓 Department of Computer Science and Engineering (CSE)   
🏫 Bangladesh Army University of Science and Technology (BAUST), Saidpur   
📧 Email: akmmasudurrahmangaurab@gmail.com   

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Support --> 

<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%AD%90%20Support&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

If you like this project, consider giving it a ⭐ on GitHub!
