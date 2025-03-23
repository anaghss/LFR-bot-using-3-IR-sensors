LFR Bot using 3 IR Sensors, Motor Driver (L298D) and Aurdino Uno

OVERVIEW-
This repository consists of instructions and code which is used to build a Line Following Bot using 3 IR Sensors, L298D motor driver and an Aurdino Uno. This robot auntonomously follows a pre-defined path which is usually marked by a line or a track.


COMPONENTS REQUIRED- 
Aurdino Uno - Microcontroller(Main controller)
L298D Motor Driver - Controls the motor
3 IR Sensors - Ascertains the line
2 DC Motors - Controls the movement of bot
Chassis - Base structure
Wheels 
Power Supply(9V or 12V battery)
Jumper wires - Connections between components.


CIRCUIT DIAGRAM-
IR Sensors to Arduino:

Left Sensor → 7

Middle Sensor → 8

Right Sensor → 9

Motor Driver (L298D) to Arduino:

Motor 1 (Left Motor)

IN1 → Pin 5

IN2 → Pin 6

ENA → 2

Motor 2 (Right Motor)

IN3 → Pin 10

IN4 → Pin 11

ENB → 3

Power Connections:

L298D VCC → 9V Battery

L298D GND → Arduino GND

L298D 5V Output → Arduino 5V

