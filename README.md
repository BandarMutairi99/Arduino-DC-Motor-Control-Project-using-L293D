# Arduino-DC-Motor-Control-Project-using-L293D

This project demonstrates how to control two DC motors using an Arduino UNO and an L293D motor driver IC. The motors perform a timed sequence of movements: forward, backward, and alternating left/right turns. 


# Objectives

- Move forward for 30 seconds

- Move backward for 60 seconds

- Alternate between left and right every second for 1 minute

- Stop both motors


# Components Required

| Component    | Quantity  |
| ------------ | --------- |
| Arduino UNO  | 1         |
| L293D IC     | 1         |
| DC Motor     | 2         |
| 9V Battery   | 1         |
| Breadboard   | 1         |
| Jumper Wires | As needed |


# the circuit

<img width="751" height="323" alt="Image" src="https://github.com/user-attachments/assets/df62763f-44ce-4715-8dac-0100afeb2aa4" />


# Circuit Connections

Motor A (Left Side):
ENA → Arduino pin 9 (PWM)

IN1 → Arduino pin 8

IN2 → Arduino pin 7

Motor B (Right Side):
ENB → Arduino pin 3 (PWM)

IN3 → Arduino pin 5

IN4 → Arduino pin 4

Power:
L293D VCC1 (logic) → 5V from Arduino

L293D VCC2 (motor power) → 9V battery

L293D GND (all grounds) → Common GND with Arduino and battery

# References

https://youtu.be/4I704RjOvgc?si=nNtC2qjGD0o9Vzrw


