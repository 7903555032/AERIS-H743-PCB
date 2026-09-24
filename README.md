# AERIS-H743 Hardware

# AERIS — Advanced Embedded Research & Intelligent Systems

A 6-layer STM32H743-based embedded development and flight-control/data-logging PCB designed as a practical hardware-design and PCB-layout project.

## Project Status

🚧 **Practice / Learning Project — Hardware Design Completed**

The PCB design phase is complete. This project is primarily a practical exercise to learn and apply professional PCB design concepts using KiCad, including schematic design, component selection, multi-layer stackup, component placement, power distribution, signal routing, high-speed interfaces, sensor interfacing, and design-rule checking.

This is **not a production-ready or professionally validated flight controller**. The design may contain mistakes or areas that require further review, optimization, and hardware validation.

The main goal of this project is to gain hands-on experience designing a complex **6-layer embedded PCB** from the ground up.

## Hardware Features

- STM32H743VIT6 — ARM Cortex-M7, up to 480 MHz
- 6-Layer PCB
- USB Type-C
- SPI / QSPI External Flash
- microSD via SDMMC
- ICM-42688-P IMU
- BME280 Environmental Sensor
- RTC
- INA219 Power Monitor
- CAN FD
- RS485
- GPS UART
- 4× ESC PWM Outputs
- SWD Debug Interface
- 3.3 V / 5 V Regulated Power Architecture

## PCB Architecture

- **L1 — Components + Critical Signals**
- **L2 — Ground Plane**
- **L3 — Power Distribution**
- **L4 — Signal Routing**
- **L5 — Ground Plane**
- **L6 — Bottom Signals + Selected Components**

## Communication Interfaces

- CAN FD
- RS485
- GPS UART
- USB
- SPI / QSPI
- I²C
- SDMMC

## PCB Design Goals

The main purpose of this project is to practice designing a relatively complex embedded PCB and understand how different parts of a real hardware system interact.

The design focuses on:

- 6-layer PCB architecture
- Power distribution
- Ground-plane design
- High-speed digital interfaces
- MCU placement and routing
- Sensor placement
- IMU placement considerations
- QSPI and SDMMC routing
- USB differential-pair routing
- CAN FD and RS485 interfaces
- ESC interfaces
- Thermal and mechanical considerations
- Custom KiCad symbols, footprints and 3D models
- PCB Design Rule Checking (DRC)
- Manufacturing preparation

## Project Structure

```text
AERIS-H743/
│
├── KiCAD/
│   └── AERIS-H743-PCB/
│       ├── AERIS-H743-PCB.kicad_pro
│       ├── AERIS-H743-PCB.kicad_sch
│       ├── AERIS-H743-PCB.kicad_pcb
│       ├── MCU_Core.kicad_sch
│       ├── POWER.kicad_sch
│       ├── Memory&Storage.kicad_sch
│       └── sensors.kicad_sch
│
├── Libraries/
│   ├── Symbols/
│   ├── Footprints.pretty/
│   └── 3D/
│
├── Documentation/
│
├── Datasheets/
│
└── README.md
