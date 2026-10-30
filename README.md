# Grade9-Temperature-Alert.
This project implements an automated, microcontroller-based thermal monitoring and alert system designed to track ambient temperature in real time. Built around an ESP32 development board and a DHT22 temperature/humidity sensor, the system continuously samples environmental conditions and provides immediate local alerts whenever temperatures cross a predefined safety threshold of 38°C. By integrating audio-visual indicators (LEDs and a buzzer), the system serves as a foundational prototype for industrial safety monitoring, server-room climate tracking, agricultural incubators, or health-screening environments. 
Key Features & ObjectivesReal-Time Data Acquisition: Continuously polls temperature and humidity data using a high-precision digital sensor. 
Dynamic Threshold Warning: Automatically triggers a multi-stage alert mechanism (activating a red warning LED and an audible buzzer) when ambient temperatures reach or exceed 38C. 
Failsafe Visual Indicators: Features distinct status indicators—a green LED for normal operating ranges 38C and a red LED for warning states. 
Virtual Prototyping: Fully simulated in the Wokwi browser-based environment, allowing rapid testing of hardware logic, pin mappings, and code execution without physical wiring constraints.
A threshold around 38°C is commonly utilized in prototyping scenarios because it mirrors low-grade fever tracking limits in health applications, localized microclimate alerts, or early-stage thermal accumulation warnings for electronics and equipment enclosures.
DHT22 Sensor	High-accuracy digital temperature and humidity sensor.
DHT22 VCC	5V
DHT22 SDA	Pin 2
DHT22 GND	GND
LED anode (+)	Pin 8 through resistor
LED cathode (−)	GND
Temperature	Expected LED
30°C	OFF
37°C	OFF
38°C	ON
42°C	ON

