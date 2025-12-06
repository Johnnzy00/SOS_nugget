# GSM + GPS Tracker Project

This project is a small, Arduino-based GSM + GPS tracking device designed to run from a Li-ion battery and send location data through a SIM800L module.
The goal is to build a compact, portable emergency tracker that can send location information when activated.

# It uses three main modules:

Arduino Nano (main controller)

SIM800L (GSM communication)

NEO-6M GPS (location tracking)


Power is handled using a TP4056 charger, LM2596 step-down regulator, and MT3608 step-up regulator to ensure stable voltages for all components.


# 📡 What This Device Does

Reads GPS coordinates

Sends them via SMS using the SIM800L

Runs from a rechargeable Li-ion battery

Charges over USB-C

Will later be built on a custom PCB and enclosed in a printed case

This makes it useful for emergency location beacons, asset tracking, or basic IoT devices.


# 🧩 Main Components

Arduino Nano

SIM800L GSM Module

NEO-6M GPS Module

TP4056 Charger Board

LM2596 Step-Down Regulator

MT3608 Step-Up Booster

Tactile button

Support capacitors

# 🗺️ Project Roadmap

 Build a working breadboard prototype

 Write and test the full firmware

 Finish and order the PCB

 Design and print the case
