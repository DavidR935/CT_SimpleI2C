# SimpleI2C

SimpleI2C is a lightweight C++ wrapper for I2C master communication on ESP32 using ESP-IDF.

## Features

- Easy I2C bus setup
- Device registration by slave address
- Write transactions
- Write-then-read transactions
- Simple integration as an ESP-IDF component

## Project Structure

```text
SimpleI2C/
├── CMakeLists.txt
├── include/
│   └── SimpleI2C.h
└── SimpleI2C.cpp
