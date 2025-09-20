# Heartbeat-Measurement-Using-8051-Microcontroller-
Project part of our Embedded systems  as a course work.

📌 **Project Overview**

This project implements a heartbeat monitoring system using the AT89C51 (8051 family) microcontroller.
A photoplethysmography-based heartbeat sensor detects pulse variations from the fingertip, and the measured heart rate is displayed in beats per minute (BPM) on a 3-digit 7-segment display.

The system demonstrates the integration of embedded hardware and firmware to achieve real-time physiological monitoring with low power consumption and portability.

⚙️ **Features**

Real-time heartbeat detection and BPM calculation

Assembly-level firmware for precise timer-based counting

Hardware circuit design optimized for low power consumption

Output displayed on a 3-digit 7-segment display

Portable and suitable for healthcare and fitness monitoring

🛠️** Components & Tools
Hardware**

AT89C51 (8051 family) Microcontroller & Development Kit

Heartbeat sensor (Photoplethysmography, LTH1550-01)

3 × 7-segment display (common anode)

Transistors (2N2222), Resistors (0.1kΩ), Capacitors (33pF, 10µF)

Breadboard, Jump wires, Power supply (5V)

Software

Keil µVision IDE – Assembly code development & debugging

**8051 Assembly Language **– Firmware implementation

📖 **Working Principle**

The sensor detects pulse variations in fingertip blood volume using infrared transmission and reflection.

The output signal is processed and fed into the microcontroller.

Timer1 is configured as an auto-reload counter to count heartbeat pulses, while Timer0 generates the required time span.

The microcontroller multiplies the pulse count to obtain BPM and displays it on the 7-segment modules.
