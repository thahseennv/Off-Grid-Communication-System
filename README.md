# Off-Grid-Communication-System
Long-range off-grid wireless communication system using ESP32 and LoRa RA-02 modules (433 MHz). Implements point-to-point protocol for reliable sensor/text data transfer between nodes, with tuned spreading factor and bandwidth for optimal range vs. data rate — built for remote monitoring and emergency use.
# Off-Grid Communication System

**ESP32 | LoRa (RA-02) | Embedded C — April 2026**

A long-range, off-grid wireless communication system built using ESP32 microcontrollers interfaced with RA-02 LoRa modules operating at 433 MHz. The system enables reliable data transmission without any dependency on Wi-Fi or cellular networks, making it suitable for remote monitoring and emergency communication scenarios.

## How It Works
Two ESP32 nodes communicate using a point-to-point protocol built on the LoRa library, transmitting and receiving sensor and text data over extended distances. Transmission parameters — including spreading factor and bandwidth — were tuned to balance communication range against data rate, ensuring reliable packet delivery even in challenging RF conditions.

## Components Used
- ESP32 Microcontroller x2
- LoRa RA-02 Module (433 MHz) x2
- Antenna
- Power supply/battery

## Key Features
- Point-to-point wireless communication with no cellular/Wi-Fi dependency
- Reliable packet delivery over long range using tuned LoRa parameters
- Optimized spreading factor and bandwidth for range vs. data rate trade-off
- Built for remote monitoring and emergency-use applications

## Applications
- Remote area sensor monitoring
- Emergency/disaster communication where infrastructure is down
- Off-grid IoT deployments
