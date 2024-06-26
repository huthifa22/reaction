# Project Specifications 

This project implements a reaction time game using an STM32F4 microcontroller. The goal is to measure a user's reaction time by seeing how fast they can press a button the moment the green LED turns on. Each round starts with a quick startup sequence for the LEDs, cycling from red to yellow to green three times. After that, there will be a slower fixed time from red to yellow and a random time from yellow to green to measure a proper reaction time. A light sequence then indicates the reaction time. If the reaction is fast, the green LED will blink fast. If it's slow, the red LED will blink. If it's average, the yellow LED will blink.

# Software 

- STM32CubeIDE

# Hardware 

- STM32F407VG microcontroller
- On board Joystick from the STM board
- Breadboard
- LEDs: Red, Yellow, Green
- Resistors: 150 ohms 
- Jumper wires

# Connections

- PA0: Joystick button input
- PA1: Red LED output
- PA3: Yellow LED output
- PA5: Green LED output


![IMG_0016](https://github.com/huthifa22/STM32F407VG-Reaction-Time/assets/105901978/9d21ee3e-8dcc-482a-9909-94df83e1dccc)

https://github.com/huthifa22/STM32-Reaction-Time-/assets/105901978/5590faad-d3b4-4f97-8ada-a7828ce8bd0f

