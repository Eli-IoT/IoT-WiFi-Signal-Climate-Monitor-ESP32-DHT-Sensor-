# IoT-WiFi-Signal-Climate-Monitor-ESP32-DHT-Sensor-
This project combines WiFi signal strength monitoring with environmental sensing using an ESP32 and a DHT11/22 sensor. It captures temperature and humidity readings and sends all data to a ThingSpeak dashboard for real-time visualization.

## 🚀 What It Does
- Measures temperature and humidity using a DHT sensor
- Detects the strongest available WiFi signal (SSID + RSSI)
- Sends collected data to the cloud (ThingSpeak)
- Visualizes the data on a live dashboard

## 🛠 Components Used
- ESP32 development board  
- DHT11 or DHT22 sensor  
- Arduino IDE  
- ThingSpeak account (free)  

## 📂 Project Structure
- `main.ino` – Main Arduino sketch with all logic
- `secrets.h` – Stores your WiFi credentials and ThingSpeak API key (excluded from version control)

## ✅ Features
- Fully offline-ready: runs on any WiFi network  
- Sends data every 15 seconds  
- Easy to expand with more sensors or platforms  
- Ideal for learning cloud integration with physical devices

## 🔧 Setup Instructions
1. Flash the code to an ESP32 using Arduino IDE  
2. Connect the DHT sensor to GPIO 4  
3. Create a ThingSpeak channel and copy your API key  
4. Edit `secrets.h` with your credentials  
5. Open the Serial Monitor to debug and view connection status  

## 📊 Live Visualization
All values (temperature, humidity, WiFi signal strength) are streamed to ThingSpeak and visualized via live updating graphs.

---
chat GPT can help you if needed
