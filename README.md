📶 ESP32 Wi-Fi RSSI Monitoring using ThingSpeak

This project demonstrates how to use an ESP32 to measure Wi-Fi signal strength (RSSI) and visualize it in real time using ThingSpeak cloud platform.

The ESP32 connects to a Wi-Fi network, reads the RSSI value, and periodically uploads it to Field 1 of a ThingSpeak channel. The data is then plotted as a graph.

🔧 Hardware Requirements

1. ESP32 Development Board

2. USB Cable

3. Wi-Fi Network

4. Laptop / PC

🧰 Software Requirements

1. Arduino IDE (v2.0 or later recommended)

2. ESP32 Board Package (by Espressif)

3. ThingSpeak Account


📁 Project Structure
ESP32-RSSI-ThingSpeak/
├── ESP32_RSSI_ThingSpeak.ino
└── README.md

🧠 How It Works

ESP32 connects to the specified Wi-Fi network

RSSI (signal strength in dBm) is read using WiFi.RSSI()

RSSI value is sent to ThingSpeak using HTTP GET request

ThingSpeak plots RSSI values as a graph
