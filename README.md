# STM32 Temperature Measurement System
# Brief Description

This project aims to implement a temperature measurement system by means of using an LM35 analog temperature sensor for outputting an analog voltage as a function with respect to the temperature, an STM32 microcontroller to handle the analog to digital conversion of the LM35's output voltage as well as conversion from that digital voltage to the actual measured temperature by way of applying a certain proportionality relationship formula (technical details are further discussed in the associated technical documentation), a USB to UART converter (for connection to a terminal screen), and a breadboard + wires to connect the hardawre components.

# Hardware Requirements:
- [ ] An **STM32L4 Microcontroller based Development Board** (the project is configured for the **STM32L496G-DISCO** board)
- [ ] An **LM35** temperature sensor
- [ ] A **breadboard** and **9 wires** for wiring the hardware components (for further details, consult the documentation)
- [ ] A **Pmod USBUART** USB to UART converter for serial communication between the board and the terminal
- [ ] **2 USB cables**, one for powering the board, and the other one for serial communication

# Software Requirements:
- [ ] The **STM32CubeIDE** integrated development environment for configuring the peripherals (The **STM32CubeMX** GUI is also included in the IDE), for programming the calculation logic of the temperature within the board (C code), and for displaying the final temperature on the terminal screen (also coded with C logic)
- [ ]  **HTerm** which plays the role of the terminal screen which the temperature will be displayed on

# Usage:
For details regarding the hardware wiring and the software configuration, one may consult the associated technical documentation.
