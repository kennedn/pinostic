# pinostic
Vehicle onboard-diagnostic (OBD) assisant built specifically for the PiGRRL Zero.

![](images/pinostic.gif)

# Overview
Pinostic is a simple GUI tool written in python with the intention of being used on a piGRRL Zero [(link)](https://learn.adafruit.com/pigrrl-zero/overview). It can feasibly be used on any linux distribution with the only pre-requisits being the following:

### Hardware
* Generic ELM327 OBD to Serial Adapter
* A car with an OBD port
### Software
* python3
* python modules obd and pygame2 (python3 -m pip install obd, pygame==2.0.0dev6)

### Features
#### Implemented
* Menu view - monitor multiple commands at once
* Graph view - shows change in command values over time
* Record and export graph data to CSV
#### To be implemented
* Load and store Menu metrics in JSON file
* Customise Menu metrics from within the GUI
