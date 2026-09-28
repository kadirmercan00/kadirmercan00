<div align="center">

# Kadir Mercan

### Senior Embedded Systems, Hardware (PCB) & IoT Engineer

*Designing production-ready hardware and mission-critical firmware — from multi-layer schematics to cloud ingestion.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kadir-mercan-/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://kadirmercan00.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kadirmercan00)

</div>

---

## 🎯 Engineering Capabilities

I design and build **end-to-end mission-critical IoT, hardware, and autonomous systems**: multi-layer controlled-impedance PCB layouts in Altium Designer, deterministic RTOS firmware (STM32 / Nordic nRF52 / ESP32), decentralized swarm robotics navigation (MAVLink / APF), and edge-to-cloud industrial telemetry pipelines.

```
  Altium PCB Layout ──► Low-Power Firmware ──► Edge Gateways ──► Cloud Ingestion ──► Autonomous Swarms
   [2-6 Layer FR-4]     [Nordic nRF52 <15µA]   [ESP32 / NimBLE]   [AWS IoT / MQTT]   [PyMAVLink 10Hz APF]
```

---

## 🛠️ Technology Stack

**Hardware & Mixed-Signal PCB Design**  
![Altium Designer](https://img.shields.io/badge/EDA-Altium_Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![KiCad](https://img.shields.io/badge/EDA-KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![DFM/DFA](https://img.shields.io/badge/Manufacturing-DFM%20%2F%20DFA-success?style=flat-square)
![RF 50 Ohm](https://img.shields.io/badge/Layout-Controlled_Impedance_50%CE%A9-purple?style=flat-square)
![Mixed-Signal](https://img.shields.io/badge/Analog-Op--Amp_Conditioned_AFE-blue?style=flat-square)

**Microcontrollers & Autonomous Avionics**  
![STMicroelectronics](https://img.shields.io/badge/STMicroelectronics-STM32_Cortex--M-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Nordic nRF52840](https://img.shields.io/badge/Nordic-nRF52840_Cortex--M4F-00A9CE?style=flat-square&logo=nordicsemiconductor&logoColor=white)
![ESP32](https://img.shields.io/badge/Espressif-ESP32_Xtensa-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ArduPilot / PX4](https://img.shields.io/badge/Autopilot-ArduPilot%20%2F%20PX4-green.svg?style=flat-square)

**RTOS & Embedded Frameworks**  
![FreeRTOS](https://img.shields.io/badge/RTOS-FreeRTOS-66AA00?style=flat-square&logo=freertos&logoColor=white)
![PlatformIO](https://img.shields.io/badge/Toolchain-PlatformIO-orange?style=flat-square&logo=platformio&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/Framework-ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![STM32 HAL](https://img.shields.io/badge/HAL-STM32Cube_HAL-03234B?style=flat-square)

**Wireless Protocols & Industrial Fieldbuses**  
![LoRa / LoRaWAN](https://img.shields.io/badge/Sub--GHz-LoRa_EBYTE_E70_30dBm-0099FF?style=flat-square)
![BLE 5.0](https://img.shields.io/badge/Wireless-BLE_5.0_Long_Range-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![MAVLink 2.0](https://img.shields.io/badge/Protocol-MAVLink_2.0-blue?style=flat-square)
![ESP-Mesh](https://img.shields.io/badge/Mesh-ESP32_PainlessMesh-red?style=flat-square)
![Modbus RS485](https://img.shields.io/badge/Fieldbus-Modbus_RTU%20%2F%20RS485-FF6600?style=flat-square)
![MQTT / TLS](https://img.shields.io/badge/Cloud-MQTT_%7C_AWS_IoT_Core-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

---

## 🚀 Featured Engineering Showcases

> ⚠️ *All showcase repositories are source-available for technical architecture evaluation under strict proprietary portfolio terms.*

| Showcase Project | Architecture & Key Highlights | Technology Stack |
|:---|:---|:---|
| **[`edge-to-cloud-iot-operations`](https://github.com/kadirmercan00/edge-to-cloud-iot-operations)** | **Flagship System:** Full-stack hardware-to-cloud infrastructure. Custom wearable badge PCB (Altium), FreeRTOS C++17 firmware with hardware mTLS, AWS IoT Core & Lambda normalizer, DynamoDB, predictive maintenance ML, and real-time operations dashboard. | Custom PCB • C++17 • AWS IoT • DynamoDB • Python ML |
| **[`smart-agriculture-lora-gateway`](https://github.com/kadirmercan00/smart-agriculture-lora-gateway)** | Precision agriculture infrastructure. Features a custom **Altium 2-layer PCB** uniting an ESP32 with an EBYTE E70 (30 dBm / 1W) LoRa modem, step-down buck power rail, live web operations portal, and 41-byte binary telemetry logging. | Altium • ESP32 • EBYTE E70 LoRa • MQTT • Web UI |
| **[`stm32-industrial-eval-board`](https://github.com/kadirmercan00/stm32-industrial-eval-board)** | Rugged mixed-signal evaluation board based on **STM32F103RDT6 (72 MHz)**. Incorporates isolated RS-485 Modbus RTU Slave, operational amplifier analog front-end (AFE) for 12-bit ADC conditioning, DAC waveform generation, and Python field diagnostic tool. | Altium • STM32F103 • RS-485 Modbus • Op-Amp AFE • Python |
| **[`swarm-uav-formation-nav`](https://github.com/kadirmercan00/swarm-uav-formation-nav)** | Autonomous multi-drone swarm formation navigation. Implements **Artificial Potential Field (APF)** collision avoidance, 10 Hz MAVLink NED velocity vectoring, ESP32 PainlessMesh ad-hoc inter-UAV telemetry, OpenCV ArUco tracking, and live offline simulator. | Python • DroneKit • MAVLink • OpenCV • APF Simulator |
| **[`nrf52-esp32-ble-iot-network`](https://github.com/kadirmercan00/nrf52-esp32-ble-iot-network)** | Hybrid industrial WSN combining ultra-low-power **Nordic nRF52840 nodes (<15 µA)** broadcasting 16-byte packed CRC-32 frames with an **Espressif ESP32 10-state deterministic gateway** featuring RF TDM coexistence and MQTT cloud delivery. | Nordic nRF52 • ESP32 • BLE 5.0 • RF Coexistence • MQTT |

---

## 📈 Field & Industrial Milestones

- **Hardware Engineering:** Designed and fabricated multi-layer PCBs compliant with IPC-2221, controlled 50Ω impedance, and industrial DFM/DFA rules.
- **Ultra-Low-Power Telemetry:** Deployed commercial sensor fleets with **3+ years single-cell battery life** (<15 µA sleep current).
- **Autonomous Swarms:** Deployed distributed formation geometry algorithms with 10 Hz real-time velocity vectoring and mesh diagnostics.
- **Industrial Coexistence:** Solved single-antenna 2.4 GHz RF contention between Wi-Fi and Bluetooth subsystems in dense edge facilities.

---

<div align="center">
  <sub>Portfolio maintained by Kadir Mercan (Mercan Studio). For technical consulting or inquiries: <a href="mailto:kadir@mercan.studio">kadir@mercan.studio</a></sub>
</div>
