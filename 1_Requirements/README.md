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
* When the light intensity on the right LDR is higher, the panel slowly travels to the right, and when the light intensity on the left LDR is higher, the panel gently goes to the left. The sun is ahead at noon, and the intensity of light on both panels is the same. In such circumstances, the panel remains stationary and does not rotate.

## Components Description

### ATmega328 Microcontroller

ATmega328 is an AVR family micro controller. It is based on advanced RISC architecture. It is an 8-bit controller. It has 32K Bytes of Programmable Flash memory, 1K Bytes of EEPROM and 2K Bytes of SRAM. It has 23 programmable I/O pins.

### LDR

Light Dependent Resistors or LDRs are the resistors whose resistance values depend on intensity of the light. As the intensity of light falling on the LDR increases, resistance value decreases. In dark, LDR will have maximum resistance.

### Servo Motor

Servo motor is used to rotate the panel.

# SWOT

## Strengths

* Ease to use as it is renewable form of energy.
* Saves the electricity bill.

## Weakness

* May create problems in rainy season.
* They are heavy and occupy more space.

## Opportunities

* Used in homes, offices, industries as more energy can be saved by rotating the panel.

## Threats

* Expensive

# 4W's and 1'H

## Who

Can be used for those who wants to save electricity bill and energy.

## Where

Used in homes, offices, industries, streetlights.

## When

When there is power outage or to save the energy.

## Why

Ease to use the solar energy.

## How

By using SimulIDE.
