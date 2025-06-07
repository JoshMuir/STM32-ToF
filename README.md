# STM32-ToF

## Overview
This project combines an STM32F103CBT6 microcontroller with a VL53L0X Time-of-Flight (ToF) sensor for distance measurement applications. It serves primarily as a learning platform for STM32 development, exploring the STM32 HAL, peripheral interfaces, and embedded systems programming concepts. The ultimate goal is to create a simple environment mapping system.

## Hardware
- STM32F114 microcontroller
- VL53L0X Time-of-Flight sensor
- I2C interface for sensor communication
- Additional components TBD

## Project Goals
- Learn STM32 development environment and toolchain using STM32CubeIDE
- Implement I2C communication with VL53L0X ToF sensor
- Process distance data for environment mapping applications
- Implement data logging functionality
- Explore power management and optimization techniques
- Potentially add visualization capabilities in future iterations

## Development Phases
1. **Setup Phase**: Configure development environment and project structure
2. **Communication Phase**: Establish I2C communication with the VL53L0X sensor
3. **Data Collection Phase**: Implement reliable distance measurement and logging
4. **Processing Phase**: Develop algorithms for interpreting spatial data
5. **Optimization Phase**: Analyze and improve power consumption
6. **Optional Extension Phase**: Add visualization capabilities

## Current Status
- Initial project setup


## TODO: 

1. Setup STM32CubeMX Environment
2. Configure STM32 pinout, setup clocks and required peripherals
3. Generate skeleton code 
4.  


## STM32 Config 

   ### Clocks 
    The STM32 runs at a maximum 72MHz

   ### Pinout


   ### Peripherals
    We will need to setup the I2C interface for communication to the ToF sensor, and a UART interface for debugging   

#### I2C Setup 
According to the datasheet, the VL53L0x can communicate with fast mode i2c at 400kHz. 
We will configure our STM to use the fast mode interface at 400kHz, but may adjust if there are communication issues in the future. 


   ### Debug mode 

