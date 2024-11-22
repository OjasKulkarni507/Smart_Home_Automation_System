Smart Home Automation System
An IoT-based project using the ESP32 microcontroller to enhance home safety, comfort, and energy efficiency. This system integrates sensors and actuators to automate tasks like temperature and humidity control, lighting, and gas detection, with manual override via a web interface.

Features
Automatic Temperature and Humidity Control: Activates the fan or heater based on sensor readings.
Motion-Activated Lighting: Automatically turns lights on or off based on light intensity and motion detection.
Gas and Fire Detection: Alerts users by activating a buzzer when unsafe levels of gas are detected.
Web Interface:
Monitor real-time temperature, humidity, and device statuses.
Toggle between automatic and manual control modes.
Manually control the heater, fan, and lights.
Components Used
Microcontroller: ESP32
Sensors:
DHT11: Temperature and humidity sensor
PIR: Motion detection
LDR: Light intensity measurement
MQ2: Gas detection
Actuators:
Relay-controlled devices: Heater, fan, and lights
Buzzer: Alerts for gas/fire detection
Power Supply: Ensure proper power for all components.
Setup and Installation
Hardware Setup:

Connect the ESP32, sensors, and actuators as per the circuit diagram (refer to CircuitDiagram.png).
Ensure proper power connections and stable Wi-Fi access.
Software Configuration:

Install the Arduino IDE.
Install necessary libraries:
DHT
WiFi
WebServer
Update the ssid and password in the code with your Wi-Fi credentials.
Upload the code (SmartHomeAutomation.ino) to the ESP32.
Access Web Interface:

After uploading, check the Serial Monitor for the ESP32's IP address.
Open the IP address in a web browser to access the interface.
Usage
Automatic Mode:
The system automatically controls devices based on sensor inputs.
Manual Mode:
Use the web interface to manually toggle the heater, fan, and lights.
