# Modular_MeshMess
Modular lora breakout boards. Try Everything! Seriously. Try. Everything.

## Introduction
I made some modular boards based on the Mikrobus specification. 

For smaller modules, they work well and can sit inside the smallest footprint that the Mikrobus specifcation allows. They all follow the same pinout, so they're easy to breadboard. For larger modules, the pins get in the way, so I've moved them to one side as a 2x8 pin block. I've also added SMT pin header pads so that it is just about possible to make it work with a compliant socket.

Where I *think* that the boards follow the Mikrobus specification correctly, I've used the logo as permitted. Where I've deviated, I've omitted it.

## How to make
Send them off to a PCB fab house and get them to make the PCBs. They're 2-layer and fairly generous with tolerances.

Solder modules and caps, resistors and mosfets down with solder paste and a hotplate.

Add pin headers by hand. The module faces upwards.

## How to use
The decoupling capacitors and small bulk capacitors are enough to use these on a breadboard.

I've made a slightly over-done MCU carrier for my beloved pro-micro board.

I'll continue to produce MCU carriers as I find time.

### Bill of Material (BOM)
The EEProm is not required for normal operation, and this includes R5, R6, and C10 that go with it.

The headers are standard 2.54mm pitch 1x8 or 2x8.

C1, C6 = 0.1uF or 1uF decoupling capacitor (0603)
C3, C9 = 22uF bulk capacitor (0805)

R3, R4 = 100kOhm resistors (0603)
Q1, Q2 = P-channel MOSFET (SOT-23), e.g. AO3401a

## License
I've not figured out the license yet, but you can assume the Gerber files are CC 4.0 BY NC ND for now.

## Acknowledgement
All errors are my own, but I would like to thank a number of people who have helped in this and my previous foundational projects:
* Iris
* vaRDas
* OpenSourceCountry
* Noon
* A.li3n
* Josh
* Mark Birss
* Vidplace7
* wehooper4
* Porkcube
* Many more that I can't remember right now.

