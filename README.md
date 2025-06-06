# 🏠 Smart Home Automation using Raspberry Pi Pico W

This project is a Smart Home Automation system developed using **Raspberry Pi Pico W**, various sensors, and **Bluetooth + WiFi connectivity** to provide real-time control and monitoring of home appliances and environmental conditions. It combines IoT, embedded programming, and wireless communication to enhance safety, comfort, and energy efficiency in a smart home environment.

---

## 🔧 Features

- 🌡️ **Temperature Monitoring** using DHT11/22 sensor
- 💨 **Gas Leakage Detection** with MQ series sensors
- 💡 **Ambient Light Detection** with LDR sensor
- 🔌 **Appliance Control via Bluetooth**
- 🌐 **WiFi Data Logging and Remote Access**
- 📟 **Real-Time LCD Display**
- 🔒 Safety alert system via buzzer and LED indicators

---

## 📷 Project Images

> *(Replace these placeholders with real images)*

![Smart Home Circuit](screenshots/circuit-diagram.png)
![Running Prototype](screenshots/working-prototype.jpg)

---

## 🧠 Technology Stack

- **Microcontroller**: Raspberry Pi Pico W
- **Communication**: WiFi (HTTP/MQTT), Bluetooth
- **Sensors**:
  - LDR (Light sensor)
  - DHT11 or DHT22 (Temperature & Humidity)
  - MQ-2/MQ-135 (Gas Sensor)
- **Output Devices**:
  - 16x2 LCD Display
  - Buzzer
  - Relay Module for Appliance Control
- **Programming Language**: MicroPython or C++
- **Platform**: Thonny / Arduino IDE

---

## 🔌 How It Works

1. The system continuously reads input from connected sensors.
2. Sends environmental data to a web dashboard (optional) via WiFi.
3. Allows the user to manually control devices (lights, fans) via Bluetooth.
4. Displays live sensor data on an LCD screen.
5. Triggers alerts when gas or temperature levels cross thresholds.

---

## 📁 Project Folder Structure

SmartHomeAutomation/
├── code/
│ ├── main.py # Main MicroPython or Arduino sketch
│ └── config.py # WiFi and threshold config
├── docs/
│ ├── circuit-diagram.png
│ └── report.pdf
├── screenshots/
│ └── working-setup.jpg
└── README.md


---

## 📦 Setup Instructions

1. Flash MicroPython or use Arduino IDE for C++ on the Raspberry Pi Pico W.
2. Connect sensors as per the provided circuit diagram.
3. Upload `main.py` to the board.
4. Monitor via serial console or LCD display.
5. Test Bluetooth control using any serial Bluetooth terminal app on a mobile phone.

---

## 💡 Future Enhancements

- 📱 Android app interface for Bluetooth and WiFi control
- 🔊 Voice control integration with Google Assistant
- 📊 Cloud-based dashboard for real-time remote monitoring
- 🌎 Integration with home automation platforms like Home Assistant

---

## 👨‍💻 Author

**Sairam Molugu**  
📧 sairam@example.com  
🔗 [GitHub Profile](https://github.com/sairam-learner)

---

## 📌 License

This project is open-source and available under the [MIT License](LICENSE).

