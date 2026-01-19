
## RF Digital Attenuator (ESP32)
A custom-designed digital RF attenuator controlled by a bare ESP32 microcontroller. This project integrates wireless control with precision RF signal conditioning on a single PCB.
<img width="687" height="578" alt="Capture1" src="https://github.com/user-attachments/assets/f3777b88-1b5f-41c6-b528-4e3d379e9226" />



<img width="887" height="722" alt="Capture" src="https://github.com/user-attachments/assets/61c8db14-c169-400d-9392-2ab0cde478de" />

## Features
Microcontroller: Bare ESP32 for compact integration.

RF Control: Digital step attenuation for signal power management.

Connectivity: Wi-Fi/Bluetooth enabled for remote signal adjustment.

Design Tool: Created using KiCad 8.0 (or current version).

## Project Structure
/esp-c3-RF.kicad_pcb: PCB layout files with RF considerations (impedance matching).

/esp-c3-RF.kicad_sch: Schematic design including the ESP32-C3 peripheral circuitry.

/Schema.pdf: High-level view of the circuit design.

/LIB_STF202-22T1G: Footprints/Symbols for specific components.

## 🛠 Hardware Details
The design focuses on maintaining signal integrity for RF paths. Key design choices include:

Impedance Matching: 50 ohm traces for RF input/output.

Power Supply: Integrated LDO to provide clean power to the C3 chip and attenuator IC.

Antenna: On-board PCB antenna.

## 📝 To-Do / Roadmap
[ ] Finalize PCB routing and ground plane stitching.

[ ] Order prototype via Lion Circuits.

[ ] Develop firmware for Web-based attenuation control.

