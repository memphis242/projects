# Project List

For the programming-related projects, I might want to make a version in C, C++,
Python, and Rust, or at least alternate between each language as the one I _first_
make a project in. It'll be an effective and fun way to keep each of those language
skills sharp and explore different language concepts.

## Pure Software

### Level 1
- → |`libsodium_playground`|
- → |`libcjson_playground`|
- `netsnmp_playground`
- `sqlite_playground`
- `openssl_playground`
- `libssh_playground`
- `libhttp_playground`
- `libpcap_playground`
- `libevent_playground`
- `zlib-ng_playground`

- → |netsp|
- alarmtimer

### Level 2
- → |tftptest| (tftp test server)
- tftp client
- http server daemon
- http client
- https server daemon
- https client
- snmpv3 server daemon
- snmpv3 client
- sftp server daemon
- sftp client
- mqtt server daemon
- mqtt client

- `network_topology_mapper` - A tool that uses SNMP and ICMP to map and visualize
  devices on a local network.

- → |The Mindfully Embedded Blog|

- → |`budget_oracle`|
- → |`active_recall`|
- → |chatlan server + local certificate authority + TUI client app|
    - Cisco Small Business WAP Series
        - Cisco WAP125, WAP150 (may be hard to find)
    - TP-Link EAP Series (Omada)
        - Omada EAP620 (AX1800) ($124.99 from store.omadanetworks.com)
        - Omada EAP723 (BE5000) ($89.99 from store.omadanetworks.com)
    - Zyxel NWA / WAC Series

- → |conficol|
- nparsy

### Level 3
- `tftpy_playground`
- [`utftp`](github.com/yogo1212/utftp) playground
- Read the code of the Linux Kernel's network [`tftp` toolset](https://git.kernel.org/pub/scm/network/tftp/tftp-hpa.git/about)

- `emg_signal_filter_sim` - A tool to simulate and apply digital filters to raw
  EMG datasets, paving the way for real-time biomedical software.

- chatlan /w chatrow
- chatlan phone app
- chatlan web app

- `a_game_of_pong`

### Level 4
- `libcurl_playground`

- → |cwe-man|

- smart home server + network
    - room thermometers
    - outdoor weather sensing
    - door sensors
    - window sensors
    - air quality sensors
    - home cameras

- open source contributions

## Electronics
### Level 1
- → |555 Timer Explorations|
- AAA Battery → Adjustable 0-20V supply
- Discrete Frequency Divider Circuit
- Basic Voltage → 5-digit 7-Segment Display
- quality audio amplifier

### Level 2
- 120VAC → 12VDC, 5VDC (constant /w trimpots)

- EMG electrode amplifier
- heart rate sensor amplifier

- Custom PoE (Power over Ethernet) extractor - A circuit to extract power and
  data from a PoE line to power small network nodes.

### Level 3
- custom zigbee supported device
- custom bluetooth supported device

### Level 4
- EMG electrode
- heart rate sensor
- multichannel EMG acquisition board - A custom PCB designed to acquire, amplify,
  and digitize multiple channels of muscle activity simultaneously.

## Embedded

### Level 1
- → |Pi Home Network|
- cryptorig

- → |UART console|
- `lwip_playground`
- `mbedtls_playground`

- ascii7seg
- PIC12F1572 bootloader

- something with the Arduino R4 Minima... TBD

- `freertos_network_node` - A basic FreeRTOS project on an ESP32/STM32 that
  periodically pings a server and logs network health.

### Level 2
- self-hosted LLM server /w 32GB of VRAM

- Bluetooth Low Energy (BLE) console
- WiFi console

- CFAG240128U0 driver
- TFTP display driver
- OLED display driver
- Electromechanical 7-segment display driver
- Regular 7-segment display shift register-based driver

- Network-controlled robotic joint - An embedded controller for a single robotic
  actuator (stepper/servo) that takes commands via a basic UDP protocol.

- Low-Power DC Motor Controller /w PIC12F1572
- FRDM phone outlet → speaker
- Pill counter

- Sprint Timer
- LED Ring
- Height Measurement
- Chat Row

### Level 3
- OTA update

- Random Row
- Calendar Heatmap

- embedded fancy business card
    - accelerometer + ultra-thin low power display
    - tilt-based game
    - max rotational speed app

- usparse

- Quick Battery Measurement
- DC Power Supply
- Frequency Sensor Emulator
- remote finder
- E-Ink Weather Reporter

- arm heart rate monitor /w flexible display

- squat form measurement device
- Portable ECG/EMG monitor - A battery-powered microcontroller device that reads
  bio-signals and streams them over BLE or Wi-Fi to a host.
- Linux-based Patient Monitoring Gateway - An embedded Linux hub (e.g. Raspberry Pi)
  that aggregates BLE/Wi-Fi data from wearable sensors (like the ECG/EMG monitor)
  and displays it on a local web dashboard.

- edge ai... (TBD)

- PIC18F4620 CAN-to-Serial Dev Board /w 16x4 LCD for Glower
- Rhythmic (drum beat pacer tool) for Dr. Green

- Sumobot
- H.A.N.K. (embedded linux)

### Level 4
- peer-to-peer playground
- Zigbee mesh 

- Rubix
- ~~PID Clock~~ → PID Pin Aim
- Battlebot

- face misrecognition alarm

- Basic TUI desktop app PIC18F CAN-to-serial dev board

- Embedded Linux board /w four ethernet ports, no wireless comms

### Level 5
- Zigbee mesh OTA

- Custom network switch management plane - Embedded firmware for a managed switch
  IC implementing basic VLAN and SNMP support.

- electronode
- uSparse
- 3-Phase induction motor driver from DC battery
- 8-bit MCU Assembly card punch machine
- 8-bit MCU Assembly card reader machine
- 8-bit MCU Assembly card runner machine

- Open-source pacemaker prototype - A highly reliable, redundant embedded system
  designed to simulate pacemaker timing and fault-tolerance.

- Rehab Robotics Control Kiosk - An embedded Linux system with a touchscreen GUI
  (using Qt or GTK) acting as the primary user interface and high-level trajectory
  planner for a rehabilitative robotic arm, communicating with lower-level
  microcontrollers over CAN bus.

- open source contributions
    - FreeRTOS

### Level 6
- canary
- Fixed-Wing Drone
- distribute-the-benchmark
- Intensive Care Unit (ICU) Ventilator Controller - A highly reliable, multi-threaded
  embedded Linux application (potentially with PREEMPT_RT patches) that handles
  complex fluid dynamics, pressure monitoring, and UI for a life-support ventilator system.

### Level 7
- Autonomous Electric Snowplow

- Embedded Linux Medical Imaging Workstation - A custom embedded OS designed to
  handle high-bandwidth data acquisition (e.g., from an MRI or ultrasound
  sensor array), perform hardware-accelerated image reconstruction (using GPUs/FPGAs),
  and render real-time medical imaging.
