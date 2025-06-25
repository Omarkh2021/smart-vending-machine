
🧠 Smart IoT Vending Machine 🍬☕
🎓 Second Place Winner – IEEE BUC SB S’25 Exhibition

🔹 Overview
This project is a Smart Vending Machine capable of:

Dispensing 4 types of sweets using RFID authentication.

Preparing customizable hot drinks with sugar control, button interface, and automated mixing.

Offering IoT integration for real-time monitoring and remote control via a mobile application.

📦 Features
🍬 Sweets Dispenser
RFID-based authentication for secure access

Servo-controlled delivery for four different sweet types

LCD display with user prompts and selection feedback

Ultrasonic sensor to detect cup presence

☕ Hot Drinks Maker
Button interface to select drink type and sugar quantity

RFID access for registered users

Automated control of pumps, heating, and stirring motors

LED indicators for drink status

Timeout mechanism to reset after inactivity

🌐 IoT Dashboard
Real-time status updates (e.g., inventory, user logs)

Remote control of core functions via Blynk or Firebase

Data logging for user access and item dispensing history

🛠️ Hardware Used
Arduino Mega 2560

MFRC522 RFID module

SG90 / MG995 Servo motors

Peristaltic pumps

Heating element with relay control

Ultrasonic sensor (HC-SR04)

16x2 LCD display with I2C

Push buttons

LEDs (status indicators)

WiFi Module (ESP8266 or NodeMCU for IoT)

📁 Folder Structure
css
Copy
Edit
├── SweetsDispenser/
│   ├── Code/
│   ├── CircuitDiagram/
│   └── Images/
│
├── HotDrinksMachine/
│   ├── Code/
│   ├── IoT_Firmware/
│   ├── CircuitDiagram/
│   └── Images/
│
├── certificate.jpg
├── README.md
└── LICENSE
🚀 How to Use
✅ Requirements
Arduino IDE

Blynk/Firebase App

Libraries: Servo.h, MFRC522.h, LiquidCrystal_I2C.h, NewPing.h, ESP8266WiFi.h, FirebaseESP8266.h

🔧 Setup
Upload the respective Arduino code to your Mega board.

Connect the components as per the CircuitDiagram.

Configure WiFi credentials and Blynk/Firebase tokens.

Power up the machine and start interacting!

📸 Demo & Media
Add demo videos or GIFs here

Sweet Dispensing: ✅

Hot Drink Making: ✅

IoT Remote Access: ✅

📜 License
This project is licensed under the MIT License.

🏆 Award
🥈 Second Place Winner – IEEE BUC SB S'25 Exhibition
Recognized for innovation, automation, and IoT integration.
