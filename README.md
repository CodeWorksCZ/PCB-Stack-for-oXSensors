# PCB Stack for oXSensors
This PCB design focuses on creating a minimalistic and efficient PCB stack for OpenXSensor project  https://github.com/mstrens/oXs_on_RP2040 , incorporating essential features such as Li-PoL  individuall cell measurement, temperature measurement using NTC, and seamless integration with external GPS modules.

Top PCB Connectors:

- NTC 10K Thermistor
- RPM -> to CDI
- ACS758 Current Sensor and Voltage measurement

Bottom PCB Connectors:

- Li-Pol Cells Measurement (up to 4S)
- GPS Module - e.g. BN-220
- ACS758 Current Sensor and Voltage measurement

PCB Stack Connectors:
![My Image](images/Connectors.png)

Wiring and assembly instructions can be found in https://github.com/CodeWorksCZ/PCB-Stack-for-oXSensors/wiki

First version does not have a possibility to connect other I2C devices.
