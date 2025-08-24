Project: Smart Water Level Indicator

Author: PURVA BHATI

🔧 Components:

Arduino Uno

HC-SR04 Ultrasonic Sensor

3x LEDs (Green, Yellow, Red)

3x 220-ohm resistors

Buzzer

LCD Display (16x2 I2C)

Breadboard and Jumper wires

📖 Description:

This project uses an ultrasonic sensor to monitor the water level in a tank. It provides visual and audible alerts via LEDs and a buzzer, and displays water level on an LCD.

💡 Features:

Real-time water level detection

LED indicators for 3-level alert (LOW, MEDIUM, FULL)

Audible alert using buzzer when tank is full

LCD display shows water level percentage

Simple and fast to build and simulate

🔌 Circuit Summary:

HC-SR04:

VCC → 5V

GND → GND

Trig → D9

Echo → D10

LCD (I2C):

SDA → A4

SCL → A5

VCC → 5V

GND → GND

Buzzer:



→ D7



→ GND

Red LED:

Anode → 220Ω Resistor → D2

Cathode → GND

Yellow LED:

Anode → 220Ω Resistor → D3

Cathode → GND

Green LED:

Anode → 220Ω Resistor → D4

Cathode → GND

📷 Simulation Platform:


Wokwi IoT Simulator
