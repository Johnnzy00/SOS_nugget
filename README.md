# GSM + GPS Tracker Project
This project is a small, Arduino-based GSM + GPS tracking device designed to run from a Li-ion battery and send location data through a SIM800L module.
The goal is to build a compact, portable emergency tracker that can send location information when activated.

# It uses three main modules:
Arduino Nano (main controller)

SIM800L (GSM communication)

NEO-6M GPS (location tracking)

Power is handled using a TP4056 charger, LM2596 step-down regulator, and MT3608 step-up regulator to ensure stable voltages for all components.


# What This Device Does
Reads GPS coordinates

Sends them via SMS using the SIM800L

Runs from a rechargeable Li-ion battery

Charges over USB-C

# PCB
! [PCB1(/PCB/pcb1.JPG)]

! [PCB2(/PCB/pcb2.JPG)]

! [PCB3(/PCB/pcb3.JPG)]

# To do list
- [ ] Build a working breadboard prototype

- [ ] Write and test the full firmware

- [x] Finish PCB

- [ ] Design and print the case
