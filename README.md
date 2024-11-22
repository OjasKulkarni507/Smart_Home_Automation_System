Smart Home Automation System
An IoT-based project designed to enhance comfort, safety, and energy efficiency. This system automates tasks like temperature and humidity control, lighting, and fire/gas detection using the ESP32 microcontroller.

Features
Temperature and Humidity Control: Maintains optimal indoor conditions automatically.
Automatic Lighting: Adjusts lights based on ambient light and room occupancy.
Fire and Gas Detection: Alerts users to potential hazards for safety.
Energy Efficiency: Reduces energy waste through intelligent automation.
Components Used
Microcontroller: ESP32 Devkit V1
Sensors:
DHT11/DHT22 for temperature and humidity
PIR sensor for motion detection
LDR for light intensity
Gas sensor (MQ-2/MQ-5) for fire and gas detection
Actuators: Relays for appliance control
Others: Jumper wires, breadboard, power supply
How It Works
Monitoring: Sensors gather data on environmental conditions and room occupancy.
Processing: The ESP32 processes sensor data to determine actions.
Automation: Relays activate/deactivate devices based on defined thresholds.
Installation
Hardware Setup:
Connect the sensors and relays to the ESP32 as per the circuit diagram.
Software Setup:
Install Arduino IDE.
Install ESP32 board support and required libraries (e.g., DHT, Adafruit_Sensor).
Upload the code to the ESP32.
Power Up: Connect the ESP32 to a power source or laptop via USB.
Usage
The system runs automatically once powered on.
Monitor and control devices via the web server interface (if implemented).
Future Enhancements
Integration with voice assistants like Alexa or Google Assistant.
Smartphone app for remote control.
Advanced analytics for energy usage.
