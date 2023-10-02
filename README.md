# House-Safety-Alarm using Ardino UNO
Creating a house safety alarm system using an Arduino Uno is a popular DIY electronics project that allows you to build a simple yet effective home security system. This project typically involves various sensors and components to detect intruders or hazardous situations and trigger an alarm or notification. Below is a basic overview of how to create a house safety alarm using an Arduino Uno:

Components Needed:

Arduino Uno (or compatible board).
Passive Infrared (PIR) motion sensor: Detects motion and presence of people.
Magnetic reed switches or door/window sensors: Detect the opening of doors or windows.
Buzzer or alarm module: Produces sound when triggered.
LEDs: For visual indication.
Breadboard and jumper wires.
Power supply for the Arduino (e.g., battery or USB).
Steps to Create the House Safety Alarm:

Setting Up the Hardware:

Connect the PIR motion sensor to one of the digital input pins (e.g., D2) on the Arduino.
Connect the magnetic reed switches to other digital pins (e.g., D3, D4) for doors/windows.
Connect the buzzer to a digital output pin (e.g., D5) for the alarm sound.
Connect LEDs to digital pins (e.g., D6, D7) for visual indicators.
Programming the Arduino:

Write an Arduino sketch (program) to read data from the PIR sensor and magnetic switches.
Define the conditions for triggering the alarm, such as detecting motion or open doors/windows.
Program the Arduino to activate the buzzer and LEDs when an intrusion is detected.
