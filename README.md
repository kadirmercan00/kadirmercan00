<div align="center">

# Kadir Mercan

### Senior Embedded Systems, Hardware (PCB) & IoT Engineer

*Designing production-grade hardware and mission-critical firmware — from schematic to cloud ingestion.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kadirmercan)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://mercan.studio)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kadirmercan00)

</div>

---

## 🎯 Engineering Capabilities

I design and build **end-to-end mission-critical IoT and autonomous systems**: multi-layer high-speed PCB layouts (Altium), deterministic low-power firmware (Nordic nRF52 / ESP32 / STM32), decentralized swarm robotics navigation (MAVLink), and edge-to-cloud industrial telemetry pipelines.

```
  Altium PCB Layout ──► Low-Power Firmware ──► Edge Gateways ──► Cloud Ingestion ──► Autonomous Swarms
       [4-8 Layers]          [Nordic nRF52]       [ESP32 / NimBLE]    [MQTT / TLS]       [PyMAVLink / APF]
```

---

## 🛠️ Technology Stack

**Microcontrollers & Autonomous Avionics**  
![Nordic nRF52840](https://img.shields.io/badge/Nordic-nRF52840_Cortex--M4F-00A9CE?style=flat-square&logo=nordicsemiconductor&logoColor=white)
![ESP32](https://img.shields.io/badge/Espressif-ESP32_Xtensa-E7352C?style=flat-square&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STMicroelectronics-STM32_Cortex--M-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Pixhawk / ArduPilot](https://img.shields.io/badge/Autopilot-ArduPilot%20%2F%20PX4-green.svg?style=flat-square)

**RTOS & Embedded Frameworks**  
![FreeRTOS](https://img.shields.io/badge/RTOS-FreeRTOS-66AA00?style=flat-square&logo=freertos&logoColor=white)
![PlatformIO](https://img.shields.io/badge/Toolchain-PlatformIO-orange?style=flat-square&logo=platformio&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/Framework-ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Nordic SoftDevice](https://img.shields.io/badge/BLE_Stack-SoftDevice%20S140-00A9CE?style=flat-square)

**Hardware & PCB Design**  
![Altium Designer](https://img.shields.io/badge/EDA-Altium_Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![KiCad](https://img.shields.io/badge/EDA-KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![DFM/DFA](https://img.shields.io/badge/Manufacturing-DFM%20%2F%20DFA-success?style=flat-square)
![RF 50 Ohm](https://img.shields.io/badge/Layout-Controlled_Impedance_50%CE%A9-purple?style=flat-square)

**Protocols & Industrial Busses**  
![BLE 5.0](https://img.shields.io/badge/Wireless-BLE_5.0_Long_Range-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![MAVLink 2.0](https://img.shields.io/badge/Protocol-MAVLink_2.0-blue?style=flat-square)
![ESP-Mesh](https://img.shields.io/badge/Mesh-ESP32_PainlessMesh-red?style=flat-square)
![MQTT](https://img.shields.io/badge/IoT-MQTT%20%2F%20TLS-660066?style=flat-square&logo=mqtt&logoColor=white)
![Modbus RTU](https://img.shields.io/badge/Fieldbus-Modbus_RTU%20%2F%20RS485-FF6600?style=flat-square)
![CAN Bus](https://img.shields.io/badge/Automotive-CAN_Bus_2.0B-darkgreen?style=flat-square)

---

## 🚀 Featured Engineering Showcases

> ⚠️ *All showcase repositories are source-available for technical architecture evaluation under strict proprietary portfolio terms.*

| Showcase Project | Architecture & Key Highlights | Technology Stack |
|:---|:---|:---|
| **[`esp32-ble-mqtt-gateway`](https://github.com/kadirmercan00/esp32-ble-mqtt-gateway)** | Deterministic 10-state FSM edge gateway. Features **hardware RF coexistence** (time-division multiplexed BLE/Wi-Fi), IEEE 802.3 CRC-32 validation, and non-volatile pulse persistence (NVS) across node brownouts. | ESP32 • NimBLE • PubSubClient • NVS • PlatformIO |
| **[`swarm-uav-formation-nav`](https://github.com/kadirmercan00/swarm-uav-formation-nav)** | Autonomous multi-drone swarm formation navigation. Implements **Artificial Potential Field (APF)** collision avoidance, 10 Hz MAVLink NED velocity vectoring, ESP32 PainlessMesh ad-hoc inter-UAV telemetry, and OpenCV ArUco optical guidance. | Python • DroneKit • MAVLink • OpenCV • PyQt5 |
| **[`nrf52840-ble-sensor-node`](https://github.com/kadirmercan00/nrf52840-ble-sensor-node)** | Ultra-low-power industrial sensor node firmware. Achieves **<15 µA deep sleep**, wear-leveled LittleFS non-volatile logging (`0xBEEF` validation), debounced interrupt service routines, and automatic refill detection. | Nordic nRF52840 • Bluefruit52 • LittleFS • FreeRTOS |
| **[`industrial-env-monitor`](https://github.com/kadirmercan00/industrial-env-monitor)** | High-reliability occupational health station. Directly interfaces Sensirion SHT35 via **raw I2C (`0x2400`)**, ScioSense CCS811 MOX gas analysis, discrete moving average CO filtering, acoustic noise windowing, and MicroSD CSV datalogging. | ESP32 • SHT35 I2C • CCS811 • MicroSD SPI • NTP |

---

## 📈 Field & Industrial Milestones

- **Ultra-Low-Power Telemetry:** Designed and deployed commercial sensor fleets with **3+ years single-cell battery life** (<18 µA sleep).
- **Industrial Coexistence:** Solved single-antenna 2.4 GHz RF contention between Wi-Fi and Bluetooth subsystems in dense edge facilities.
- **Autonomous Swarm Avionics:** Implemented distributed formation geometry algorithms with real-time velocity vectoring and mesh diagnostics.
- **Hardware Reliability:** Delivered multi-layer PCB designs compliant with IPC-2221 and DFM/DFA assembly tolerances.

---

<div align="center">
  <sub>Portfolio maintained by Kadir Mercan (Mercan Studio). For technical consulting or inquiries: <a href="mailto:kadir@mercan.studio">kadir@mercan.studio</a></sub>
</div>
