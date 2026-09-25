# Hi, I'm Pei An Chen

> Embedded biomedical sensing, research instrumentation, and FPGA systems

![Verilog](https://img.shields.io/badge/Verilog-1E4A7A?style=flat-square)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Zephyr](https://img.shields.io/badge/Zephyr_RTOS-684D8A?style=flat-square&logo=zephyrproject&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-RTL_Design-C63C15?style=flat-square)

I develop end-to-end experimental systems that connect **sensors and actuators**, **embedded firmware**, **mobile or web applications**, and **analysis-ready data**. My repositories span wearable biosensing, electrochemical and microfluidic instruments, automated biological imaging, reduced-gravity control, and FPGA reliability logic.

## Engineering Portfolio

| Domain | What I build | Core technologies |
| --- | --- | --- |
| Wearable biosensing | Multi-location temperature and sweat-pressure sensing, synchronized physiological data, and device history | Nordic nRF, BLE, MLX90614, Android, Wear OS |
| Embedded-to-cloud platforms | Mobile acquisition, offline persistence, device identity, authenticated synchronization, and research dashboards | Kotlin, Jetpack Compose, Room, Firebase, Flask |
| Electrochemical instrumentation | Portable chronoamperometry systems with single-button workflows, TFT feedback, and SD logging | EmStat Pico, C/C++, SPI, MethodSCRIPT |
| Microfluidic systems | Pump and valve sequencing, stop-flow observation, smartphone imaging, and payload integration | ESP32, PlatformIO, PDMS, micropumps, Android |
| Space and biological experiments | Periodic high-resolution imaging and feedback-controlled reduced-gravity motion platforms | ESP32-S3, OV5640, closed-loop control, PID |
| FPGA and digital systems | Verilog RTL, state machines, memories, processors, HPS-FPGA integration, and self-checking verification | Verilog, Quartus, Qsys, Questa, DE1-SoC |

## System Design Focus

- **Cross-layer integration**: firmware, communication, application state, persistence, and analysis are designed as one system.
- **Hardware-aware software**: timing, power, memory retention, calibration, radio behavior, and physical interfaces are treated as design constraints.
- **Evidence-based validation**: simulation, successful builds, bench measurements, and experimentally verified behavior are documented separately.
- **Research usability**: projects emphasize reproducible acquisition, interpretable data, clear procedures, and maintainable iteration.

## Featured Projects

| Project | Description | Technologies |
| --- | --- | --- |
| [ThermoPatch](https://github.com/chen861019/ThermoPatch) | Multi-sensor BLE body-temperature platform with Android visualization, Firebase synchronization, and OTA firmware updates | Kotlin, Jetpack Compose, BLE, Firebase, nRF52840 |
| [SpaceCellCam](https://github.com/chen861019/SpaceCellCam) | ESP32-S3 and OV5640 platform for periodic, LED-assisted high-resolution biological imaging | C++, Python, ESP32-S3, OV5640, microSD |
| [Space BMC Core RTL](https://github.com/chen861019/Space-BMC-Core-SEMC) | Verilog-2001 reliability-control building blocks with cycle-accurate, self-checking verification | Verilog, Questa, FPGA |
| [nRF54L15 MLX90614](https://github.com/chen861019/nRF54L15_MLX90614) | Zephyr/NCS infrared-temperature firmware and low-power analysis for the XIAO nRF54L15 | C, Zephyr, I2C, BLE |
| [Galaxy Watch Sensor Monitor](https://github.com/chen861019/GalaxyWatchSensorMonitor) | Wear OS application for Samsung skin-temperature acquisition and sensor research | Kotlin, Wear OS, Samsung Health Sensor SDK |
| [NYCU-AFPGA](https://github.com/chen861019/NYCU-AFPGA-Labs) | Detailed Verilog and DE1-SoC labs covering digital logic, memories, processors, and HPS-FPGA integration | Verilog, Quartus, Qsys, DE1-SoC |

## Current Direction

- Building reliable low-power, multi-device wearable sensing workflows
- Integrating biosignal, electrochemical, microfluidic, and imaging data into research-ready systems
- Developing FPGA control and reliability modules with reproducible verification
- Improving closed-loop motion platforms for reduced-gravity experiments

![Top languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=chen861019&theme=github)
