# 🏠 Room Automation using ESP32 & Blynk

This project demonstrates a **Wi-Fi based Room Automation System** using **ESP32** and **Blynk IoT Platform**.  
Users can remotely control **fans and lights** through a mobile application over the internet.

---

## 🚀 Features
- Control appliances from anywhere using Wi-Fi  
- Mobile app based control using Blynk  
- Real-time response  
- Simple and reliable relay switching  
- Scalable for more appliances  

---

## 🧰 Components Used
- ESP32 Development Board  
- 4-Channel Relay Module  
- Fan (AC Load)  
- Light Bulbs  
- Wi-Fi Network  
- Connecting Wires  
- Power Supply  

---

## 🔌 Pin Configuration

| Appliance | ESP32 GPIO |
|----------|-----------|
| Fan 1 | GPIO 16 |
| Fan 2 | GPIO 17 |
| Light 1 | GPIO 23 |
| Light 2 | GPIO 25 |

> ⚠️ Relays are **Active LOW**  
> LOW → ON, HIGH → OFF

---

## 📱 Blynk Configuration
- Platform: ESP32  
- Buttons Mode: Switch  
- Virtual Pins:
  - V0 → Fan 1  
  - V1 → Fan 2  
  - V2 → Light 1  
  - V3 → Light 2  

---

## ⚙️ Working Principle
1. ESP32 connects to Wi-Fi and Blynk Cloud  
2. User presses buttons on Blynk App  
3. ESP32 receives command via virtual pins  
4. Corresponding relay switches ON/OFF  
5. Appliance state changes instantly  



---

## 📌 Applications
- Smart Homes  
- Hostels & Rooms  
- Energy management  
- IoT learning projects  

---

## 👤 Author
**Mohammad Zakariya**  
Electronics & Communication Engineering  
Embedded Systems | IoT | Arduino | ESP32  

---

## ⭐ Future Enhancements
- Voice control (Alexa / Google Assistant)  
- Timer & scheduling  
- Sensor-based automation  
- Energy monitoring  

---

⭐ If you like this project, don’t forget to **star the repository**!
