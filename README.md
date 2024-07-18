# Home Automation System

## Description
This Arduino-based project implements a room automation system using sensors and actuators. It includes functionality for controlling lights and fans based on occupancy and temperature conditions in two separate rooms. The system uses a PIR motion sensor to detect occupancy and temperature sensors to monitor room temperature. It provides automated control of lights and fans to enhance energy efficiency and user comfort.

## Components Used
-> Arduino Uno <br>
-> PIR Motion Sensor <br>
-> Temperature Sensors <br>
-> Relay Modules <br>
-> LEDs <br>
-> LCD Display (16x2) <br>
-> Other basic electronic components (resistors, wires, etc.) <br>

##Features
<b>Room 1 Automation:<b>

Controls room light based on occupancy.
Activates fan based on temperature threshold.
Room 2 Automation:

Controls LED indicator based on occupancy.
Activates fan based on temperature threshold.
LCD Display:

Shows room status and welcome messages.
Temperature Monitoring:

Displays real-time temperature values on the LCD.
Installation
Hardware Setup:

Connect the PIR motion sensors, temperature sensors, relays, LEDs, and LCD display to the Arduino Uno as per the circuit diagram.
Software Setup:

Install the necessary libraries:
Adafruit LiquidCrystal library for the LCD display.
Upload the room_automation.ino sketch to your Arduino Uno using the Arduino IDE.
Run the System:

Power up the Arduino Uno.
Observe the LCD display for room status and temperature readings.
Test the automation system by entering and exiting rooms to observe light and fan control based on occupancy and temperature.
Circuit Diagram
Include a brief description of the circuit setup and a schematic diagram (if available) to help users replicate the setup.

Usage
Room 1:
Enter Room 1 to activate the light and fan based on occupancy and temperature conditions.
Room 2:
Enter Room 2 to activate the LED indicator and fan based on occupancy and temperature conditions.
## Screenshots
![Screenshot 2024-07-18 225615](https://github.com/user-attachments/assets/8138ad40-c6a0-4bbe-bb31-538c8f9c288b)
