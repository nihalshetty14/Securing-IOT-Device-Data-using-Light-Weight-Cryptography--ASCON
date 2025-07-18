# Securing IoT Device Data using Light Weight Cryptography - ASCON

IoT devices often face significant constraints in processing power, memory, and energy, which makes implementing traditional cryptographic solutions challenging. This project leverages ASCON, a lightweight authenticated encryption algorithm, to secure data transmission in IoT environments efficiently. It provides strong confidentiality, integrity, and authenticity guarantees while maintaining minimal computational overhead.

The repository contains source code and practical examples showing how ASCON can be integrated with embedded devices such as ESP32, enabling real-time encryption of sensor data. This approach addresses critical security concerns in IoT applications, such as data interception and tampering, without compromising device performance or battery life.

## Usage

- Deploy the provided code on an IoT device like ESP32 with connected sensors.
- The system encrypts sensor data using the ASCON algorithm before transmission over networks such as Wi-Fi or Bluetooth.
- On the receiver side, the encrypted data can be decrypted to retrieve accurate and tamper-proof sensor readings.
- Configuration parameters such as encryption keys and communication protocols can be adjusted within the source code to fit different use cases.

## Features

- Lightweight authenticated encryption with ASCON optimized for IoT devices.
- Secure real-time encryption and decryption of sensor data.
- Low resource consumption suitable for embedded and battery-powered devices.
- Example integration with ultrasonic sensors and ESP32 microcontroller.
