# 🌿 Solar Grass Cutting Robot with Obstacle Avoidance

A smart, eco-friendly grass-cutting robot powered by solar energy. This project combines **IoT**, **embedded systems**, and **automation** to create a fully functional robot that can cut grass autonomously, avoid obstacles, and be remotely controlled using the **Blynk** app.

---

## 📌 Features

- ☀️ **Solar-Powered** – Uses a 12V solar panel to charge a Li-ion battery
- 🤖 **Obstacle Avoidance** – Ultrasonic sensor detects and avoids obstacles
- 📱 **IoT Control** – Controlled via Blynk app in both manual and auto mode
- 🔋 **Rechargeable** – Powered by 12V 7Ah lithium-ion battery with TP4056 module
- 🛡️ **Safe Operation** – Stops blade motor near humans/objects with alarm
- 🧠 **Microcontroller-based** – Uses **ESP8266 NodeMCU** and **Arduino UNO**

---

## 🧠 Tech Stack

| Module         | Description                          |
|----------------|--------------------------------------|
| **ESP8266**    | Wi-Fi-enabled microcontroller (IoT)  |
| **Arduino UNO**| Controls DC motors & sensors         |
| **Blynk App**  | Android app to control the robot     |
| **HC-SR04**    | Ultrasonic sensor for object detection |
| **L293D Shield** | Motor driver for 4x 300 RPM motors |
| **775 DC Motor**| Grass cutting blade driver          |
| **TP4056**     | Battery charging & protection module |
| **Relay**      | Controls cutter motor on/off         |

---

## 🔧 How It Works

1. **Solar panel** charges the 12V battery via TP4056.
2. **ESP8266** connects to Wi-Fi and receives commands from Blynk.
3. **Ultrasonic sensor** detects obstacles. If one is found:
   - Grass cutter stops
   - Buzzer activates
   - Robot turns to a safe path
4. In **manual mode**, user can control via app joystick.
5. In **auto mode**, the robot navigates autonomously.

---


