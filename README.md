# EEA Home Automation Project with ESP32 and Blynk

## Overview

This project implements a Smart Home System using ESP32 and the Blynk IoT platform. The system allows users to control various devices and components remotely through the Blynk app. It is designed to operate both with and without an internet connection, providing flexibility in usage scenarios.

## Components

- **ESP32 DEVKIT V1 DOIT** - 1
- **2.2uF 250V AC** - 1
- **3.3uF 250V AC** - 1
- **Diode 1N4007** - 7
- **5mm LED** - 10
- **BC547 NPN Transistor** - 7
- **510-ohm 1/4w** - 7
- **1k 1/4w** - 10
- **220k 1/4w** - 2
- **2.2-ohm 1/2w** - 2
- **5V SPDT Relay** - 7
- **SWITCH SPDT SLIDER** - 1
- **Optocoupler PC-817C** - 7
- **HLK-5M05 or HLK-10M05** - 1
- **Male & Female Berg Strips** - -
- **3-PIN & 2-PIN Terminal Connector** - 

## Libraries Used

- **Blynk Library (Version 1.1.0)**
- **IRremote Library (Version 3.6.1)**
- **DHT Library (Version 1.4.3)**

## Mandatory Settings in Code
-  ** BLYNK_TEMPLATE_ID BLYNK_DEVICE_NAME Auth Token,
-  **WiFi Credentials
-  **HEX codes of the IR remote.
-  
## Benefits and Impact

- **Power Supply:** The system operates efficiently with a 5V power supply, ensuring all internal components receive the necessary voltage.

- **Remote Connectivity:** The integration with the Blynk app and Wi-Fi provides seamless remote control of connected devices. Users can conveniently manage and monitor their home automation system from anywhere with internet access.

- **Versatile Usage:** The system is designed to work seamlessly in both internet-connected and offline environments, offering flexibility in different usage scenarios.

- **Power-Saving Feature:** A single-button feature is incorporated, enabling users to efficiently save power by turning off all connected devices with a simple press. This provides a convenient way to manage energy consumption and enhance overall efficiency.



```cpp
#define BLYNK_TEMPLATE_ID "Your_Blynk_Template_ID"
#define BLYNK_DEVICE_NAME "Your_Device_Name"
#define AUTH_TOKEN "Your_Auth_Token"
#define WIFI_SSID "Your_WiFi_SSID"
#define WIFI_PASS "Your_WiFi_Password"
#define IR_REMOTE_HEX_CODES "Your_IR_Remote_Hex_Codes"
