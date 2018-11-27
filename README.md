# MOSH
### Arduino Project in 5th year ISS at INSA Toulouse

## Overview
This repository contains the work produced during the course of Microcontroler and Open-Source Hardware (MOSH) of the 5th year Innovative Smart Systems (ISS) at INSA Toulouse. This work was produced by Alex Noize and Mathieu Raynaud.

The aim of this project was to design a complete PCB (Printed Circuit Board) implementing a double layer transimpedance amplificator assembly. This circuit is then used plugged to an Arduino board and a LoRa antenna to collect data from a gaz sensor and send it through a LoRa network.

## Double layer transimpedance amplificator
Let's have a look to the electrical circuit:

![alt text](https://github.com/AlexNoize/MOSH/blob/master/Screens/Scheme.PNG "Electrical scheme")

On the left of the scheme, the entry resistor (R1) protect the operational amplifier from the electrostatic discharges, and is associated to the C1 capacitor to filter the voltage noises.
