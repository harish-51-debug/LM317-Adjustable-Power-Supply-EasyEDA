# LM317-Adjustable-Power-Supply-EasyEDA
Designing a Power Supply Circuit In Pcb 

## Project Overview

This project focuses on the design and simulation of an LM317-based Adjustable DC Power Supply using EasyEDA. The circuit converts an unregulated DC input voltage into a stable and adjustable DC output voltage suitable for powering embedded systems, sensors, microcontrollers, and electronic prototypes.

The project demonstrates fundamental concepts of power electronics, voltage regulation, circuit protection, schematic design, and PCB development.

---

## Objectives

- Design a regulated DC power supply using LM317.
- Generate a stable adjustable output voltage.
- Implement protection mechanisms using diodes.
- Learn schematic capture and PCB design using EasyEDA.
- Understand voltage regulation principles and component selection.

---

## Features

- Adjustable output voltage
- Stable DC output
- Input and output filtering
- Reverse current protection
- LED power indicator
- EasyEDA schematic design
- PCB-ready design

---

## Components Used

| Component | Quantity | Purpose |
|------------|------------|------------|
| LM317T Voltage Regulator | 1 | Adjustable voltage regulation |
| 240Ω Resistor | 1 | Voltage setting |
| 2kΩ Resistor | 1 | Output voltage adjustment |
| 1kΩ Resistor | 1 | LED current limiting |
| Red LED | 1 | Power indication |
| 100nF Capacitor | 2 | Noise filtering |
| 100µF Capacitor | 1 | Output smoothing |
| Protection Diodes | 2 | Circuit protection |
| DC Input Connector | 1 | Power input |

---

## Software and Tools

- EasyEDA
- Circuit Simulation
- PCB Design Environment
- GitHub

---

## Circuit Description

The LM317 voltage regulator is configured as an adjustable regulator. The output voltage is determined by the resistor network connected to the ADJ pin. Input and output capacitors are used to improve voltage stability and reduce noise. Protection diodes prevent damage caused by reverse current conditions. An LED indicator shows the power status of the circuit.

---

## Working Principle

1. Unregulated DC voltage is applied at the input.
2. LM317 regulates the voltage to a stable output level.
3. The resistor network sets the desired output voltage.
4. Capacitors filter noise and ripple.
5. Protection diodes safeguard the regulator.
6. LED indicates successful power delivery.

---

## Applications

- Embedded Systems
- Microcontroller Projects
- Arduino Power Supply
- Sensor Interfaces
- Electronics Laboratory Experiments
- Educational Learning Projects

---

## Skills Demonstrated

- Power Supply Design
- Analog Electronics
- Voltage Regulation
- Circuit Simulation
- PCB Design
- Electronic Component Selection
- Hardware Debugging
- EasyEDA
- Engineering Documentation

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

- Designing voltage regulator circuits
- Selecting electronic components
- Using EasyEDA for schematic design
- Understanding power electronics fundamentals
- Circuit simulation and validation
- PCB design workflow
- GitHub project documentation

---

## Future Improvements

- Adjustable output using potentiometer
- Current limiting protection
- Over-voltage protection
- Custom PCB fabrication
- Digital voltage display integration

---

## Repository Contents

```text
README.md
LM317-Adjustable-Power-Supply-EasyEDA.json
LM317_Schematic.png
PCB_Layout.png
Simulation_Result.png
