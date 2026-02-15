# Alarm Clock Using Digital Logic Design ⏰

## Introduction
This project demonstrates the design and implementation of a basic alarm clock using digital logic design principles. The main objective of this project is to understand how simple electronic components and logic circuits can be used to create a functional alarm system. The alarm is triggered using an IR-based detection mechanism and indicated through a buzzer.

This project is useful for students learning digital electronics, logic circuits, and basic hardware design.

---

## Components Used
1. **9V Battery**  
   Used as the main power supply for the circuit.

2. **IR Receiver**  
   Detects infrared signals emitted by the IR LED and provides an output signal to the logic circuit.

3. **IR LED**  
   Emits infrared light continuously, which is detected by the IR receiver.

4. **Buzzer**  
   Acts as the alarm output device. It produces sound when activated by the logic circuit.

5. **Resistors**  
   - **390Ω Resistor**: Limits current to protect the IR LED and other components.  
   - **1Ω Resistor**: Used for voltage and current regulation in the power section of the circuit.

---

## Working Principle
The working of the alarm clock is based on infrared signal detection and digital logic control. The IR LED continuously emits infrared radiation. When the IR receiver detects this infrared signal, it generates an electrical output.

This output is fed into the digital logic circuit. When the predefined logic condition is satisfied, the circuit activates the buzzer. The buzzer then produces sound, indicating that the alarm has been triggered.

The resistors ensure proper current flow throughout the circuit and prevent damage to sensitive components. The entire circuit is powered using a 9V battery.

---

## Circuit Diagram
The circuit consists of the following blocks:

- **Power Supply (9V Battery):** Supplies power to all components  
- **IR LED:** Emits infrared signal  
- **IR Receiver:** Detects infrared signal  
- **Digital Logic Circuit:** Processes the signal  
- **Buzzer:** Produces alarm sound  

*(Circuit diagram image is attached in this repository)*



