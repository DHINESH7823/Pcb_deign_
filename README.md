# ESP32 RS-485 / Ethernet Interface Board

Custom PCB integrating an **ESP32** microcontroller with **RS-485** and **Ethernet** connectivity, designed in **EasyEDA**.

## Overview

This board combines wireless (Wi-Fi/BLE via ESP32) and wired networking/communication options on a single board, making it suitable for industrial automation, IoT gateways, or Modbus-to-Ethernet bridge applications.

## Key Components

| Component | Function |
|---|---|
| ESP32 | Main microcontroller (Wi-Fi/BLE, processing) |
| MAX485 | RS-485 transceiver for serial communication (e.g. Modbus RTU) |
| ENC28J60 | SPI-based Ethernet controller |
| RJ45 Connector | Physical Ethernet port |


## Power Supply

- Input voltage: 5V
- Onboard regulator: 3.3V

## Design Files

- `*.json` — EasyEDA source project file
- `schematic.png` / `schematic.svg` — Schematic preview
- `pcb-layout.png` / `pcb-layout.svg` — PCB layout preview
- Gerber files (if included) — for fabrication

## Tools Used

- [EasyEDA](https://easyeda.com/) — schematic capture and PCB layout

## Use Case

_Describe what you built this for — e.g. "Modbus RTU to Ethernet gateway for industrial sensor monitoring."_

## License

_Add a license if you want others to reuse this design (e.g. MIT, CC-BY-SA). Leave blank if all rights reserved._

## Notes

_Add any known issues, revision history, or future improvements here._# MY_PCB_DESIGN
EasyEDA schematic and PCB layout files for INTERFACING ESP32 ,MAX 485 ,ENC28J60,and RJ45 for monitoring circuit  
