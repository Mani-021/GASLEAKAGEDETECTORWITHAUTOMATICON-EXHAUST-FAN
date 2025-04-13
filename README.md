# 🚨 GAS LEAKAGE DETECTOR WITH AUTOMATIC ON-EXHAUST FAN 🌀  
**Project Title:** #GASLEAKAGEDETECTORWITHAUTOMATICON-EXHAUST-FAN  

A smart, safety-first project that **detects gas leakage** using an **MQ2 sensor** and **automatically activates an exhaust fan** 💨 via a **relay module** and **DC motor**. Ideal for homes, labs, and mobile kitchens — keeping you safe, always! 🛡️🏠

---

## 📦 Components Used

🔹 MQ2 Gas Sensor 🧪  
🔹 5V Relay Module ⚡  
🔹 DC Motor with Exhaust Fan 💨  
🔹 Battery (9V or 12V) 🔋  
🔹 Connecting Wires & Breadboard 🧵  
🔹 (Optional) Microcontroller like Arduino 🤖  

---

## ⚙️ Working Principle

1. 🧪 The **MQ2 sensor** detects gases like LPG, propane, or methane.  
2. 🚨 Once the gas concentration crosses a threshold, it outputs a HIGH signal.  
3. ⚡ The **5V Relay** receives the signal and switches ON.  
4. 🌀 The **DC motor-powered exhaust fan** turns ON, ventilating the area.  
5. ✅ When gas levels normalize, the fan turns OFF automatically.

---

## 🔌 Connection Guide

📌 Follow these steps to wire up your components correctly:

### 🔋 Power Connections:
- MQ2 VCC → Battery + (5V)  
- MQ2 GND → Battery -  
- Relay VCC → Battery +  
- Relay GND → Battery -  

### 📶 Signal Connections:
- MQ2 Digital Out → Relay IN  

### 💨 Exhaust Fan Connections (via Relay):
- Relay NO (Normally Open) → DC Motor +  
- DC Motor - → Battery -  

🛠️ *Tip:* If the MQ2 sensor can't drive the relay directly, use a transistor (e.g., 2N2222 or BC547) for signal amplification.

---

## 🧪 Testing Steps

1. 🔥 Bring an unlit gas lighter or safe gas source near the MQ2 sensor.  
2. 💡 If gas is detected, the sensor will output HIGH.  
3. ⚡ Relay activates, and...  
4. 🌀 Exhaust fan turns ON to clear the gas.  
5. ✅ When the gas clears, the fan turns OFF.

---

## 🛠 Applications

🏠 Kitchen Gas Safety System  
🏭 Industrial Storage Units  
🚐 RVs / Food Trucks  
🔬 Chemical Labs  

---

## 🌟 Future Upgrades

📲 Integrate IoT (WiFi/NodeMCU) for phone alerts  
📟 Add OLED/LCD display for gas levels  
🔔 Buzzer alarm for audible warnings  
🔋 Rechargeable battery or solar panel system  

---

## ⚠️ Safety Tips

❗ Always test in a **well-ventilated** area  
❌ Never use actual leaking gas for testing  
🧪 Use a lighter or small gas spray at a safe distance  
🔌 Ensure secure connections to avoid short circuits

---

## 🧠 Summary

This project offers a **low-cost, DIY gas detection system** with **automated ventilation** — a life-saving application using simple electronics. Great for hobbyists, students, and home safety projects! 👨‍🔧👩‍🔧  

---

### 🚀 Made with curiosity, safety & innovation ❤️  
![Screenshot 2025-04-13 175743](https://github.com/user-attachments/assets/ad5369ac-beb7-4756-a51f-abcefb3a6f04)
![Screenshot 2025-04-13 175711](https://github.com/user-attachments/assets/d7d3a311-4aed-472d-85c1-ea5ede844cd0)
