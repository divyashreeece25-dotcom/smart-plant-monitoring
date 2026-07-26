🌱 Smart Plant Monitoring System

📖 Overview
The Smart Plant Monitoring System is an IoT-based project designed to monitor soil moisture, temperature, and humidity in real time. The system automatically controls irrigation using a water pump whenever the soil moisture level falls below the required threshold.

The project is built using an ESP8266 (NodeMCU) microcontroller and can also be monitored and controlled remotely using the Blynk mobile application.



 Objectives

- Monitor soil moisture in real time.
- Measure temperature and humidity using DHT11.
- Automatically control irrigation.
- Enable manual ON/OFF control using the Blynk App.
- Reduce water wastage.
- Support smart agriculture using IoT.



 Hardware Components

- ESP8266 NodeMCU
- Soil Moisture Sensor
- DHT11 Temperature & Humidity Sensor
- PIR Motion Sensor
- 5V Relay Module
- 16×2 I2C LCD Display
- Water Pump
- Push Button
- Breadboard
- Connecting Wires
- 18650 Battery



Software Used

- Arduino IDE
- Blynk IoT Platform
- ESP8266 Board Package



Working Principle

1. Soil moisture sensor reads soil condition.
2. DHT11 measures temperature and humidity.
3. ESP8266 sends sensor data to the Blynk cloud.
4. Sensor values are displayed on the LCD.
5. If soil moisture is low, the relay switches ON the water pump automatically.
6. Users can also manually control the pump using the Blynk mobile application.



Features

-Real-time monitoring
-Automatic irrigation
-Manual control through Blynk
-LCD display
-Low-cost IoT solution
-Water conservation





Blynk Dashboard

Virtual Pins:

-V0 → Temperature
-V1 → Humidity
-V12 → Pump Control



📊 Results

- Real-time monitoring achieved.
- Automatic irrigation working successfully.
- Manual control through Blynk.
- LCD displays live sensor values.
- Stable IoT communication.



🚀 Future Improvements

- AI-based crop analysis
- Weather forecasting integration
- Solar-powered irrigation
- Cloud data analytics
- Mobile notifications

