# AERIS-H743 Hardware
# AERIS — Advanced Embedded Research & Intelligent Systems

Professional STM32H743-based 6-layer embedded development and flight-control/data-logging board.

## Features

- STM32H743VIT6 — ARM Cortex-M7, up to 480 MHz
- 6-Layer PCB
- USB Type-C
- SPI / QSPI External Flash
- microSD via SDMMC
- ICM-42688-P Class IMU
- BME280 Environmental Sensor
- RTC
- INA219 Power Monitor
- CAN FD
- RS485
- GPS UART
- 4× ESC PWM Outputs
- SWD Debug
- 3.3 V / 5 V Regulated Power Architecture

## PCB Architecture

- L1 — Components + Critical Signals
- L2 — Solid GND
- L3 — Power Distribution
- L4 — Signal Routing
- L5 — Solid GND
- L6 — Bottom Signals + Selected Components

## Communication Interfaces

- CAN FD
- RS485
- GPS UART
- USB
- SPI / QSPI
- I²C
- SDMMC

## Project Structure

```text
AERIS-H743/
│
├── Hardware/
│   ├── Schematic/
│   ├── PCB/
│   ├── Libraries/
│   └── Documentation/
│
├── Firmware/
│
├── Datasheets/
│
└── README.md

Status

🚧 Under Development
