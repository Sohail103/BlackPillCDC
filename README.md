9# STM32 Blackpill - USB CDC + I2C1 Setup

This project is the initial STM32CubeIDE setup for USB CDC and I2C1 communication on the STM32F401CC Blackpill board.

## Features
- USB CDC (Virtual COM Port)
- I2C1 enabled
- STM32CubeMX .ioc configuration included

## How to Build
Open with STM32CubeIDE and build. Flash using ST-Link or DFU.
Use linker flags -u_printf_float