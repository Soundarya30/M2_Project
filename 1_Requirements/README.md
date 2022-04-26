# Introduction
## Solar Panel Position By Tracking Sun


A solar panel is a device that absorbs the sun's rays and converts them into electricity. This energy can be used as needed or as a straight replacement for grid-supplied electricity. Solar panels should absorb as much energy as possible in order to make the most efficient use of solar energy. This is only possible if the panels are always pointing in the direction of the Sun. As a result, solar panels should rotate towards the direction of the sun to absorb more energy from it. This project is about a circuit that rotates a solar panel in response to the sun's location.

![solar panel](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSd6-Iv49C7uf8oDBvVlUaoKsjf49Qu1zWKoQ&usqp=CAU)

## Research

Solar panel position by tracking sun is a project which uses ATmega328 Micro Controller and set the position of the solar panel to the direction of the sun.

# Software Used

SimulIDE

# WORKING PRINCIPLE

* Two LDRs, a solar panel, a servo motor, and an ATmega328 Microcontroller make up the Sun tracking solar panel.On the solar panel's edges, two light-dependent resistors are positioned. When light falls on a light dependent resistor, it produces a low resistance. The panel is rotated in the direction of the Sun by a servo motor connected to it. The panel is set up in such a way that the light from two LDRs is compared, and the panel is rotated towards the LDR with the highest intensity, i.e. the least resistance. The panel is rotated at a specific angle using a servo motor.


## Components Description

### ATmega328 Microcontroller

ATmega328 is an AVR family micro controller. It is based on advanced RISC architecture. It is an 8-bit controller. It has 32K Bytes of Programmable Flash memory, 1K Bytes of EEPROM and 2K Bytes of SRAM. It has 23 programmable I/O pins.

### LDR

Light Dependent Resistors or LDRs are the resistors whose resistance values depend on intensity of the light. As the intensity of light falling on the LDR increases, resistance value decreases. In dark, LDR will have maximum resistance.

### Servo Motor

Servo motor is used to rotate the panel.
