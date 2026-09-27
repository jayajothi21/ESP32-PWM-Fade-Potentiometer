# ESP32 PWM Fade using Potentiometer

## Project Description

This project demonstrates LED brightness control using PWM (Pulse Width Modulation) with an ESP32 and a potentiometer.

The potentiometer is used to control the brightness of the LED. When the potentiometer is rotated, the LED brightness increases or decreases according to the potentiometer value.

## Components Used

- ESP32
- LED
- Potentiometer
- Resistor
- Wokwi Simulator

## Connections

- Potentiometer VCC → ESP32 3V3
- Potentiometer GND → ESP32 GND
- Potentiometer SIG → GPIO 34
- LED → GPIO 2

## Working

1. The potentiometer provides an analog value.
2. ESP32 reads the potentiometer value.
3. The analog value is converted into a PWM value.
4. The PWM signal controls the LED brightness.
5. When the potentiometer is rotated, the LED brightness changes.
6. Higher potentiometer value makes the LED brighter.
7. Lower potentiometer value makes the LED dimmer.

## PWM

PWM stands for Pulse Width Modulation.

PWM is used to control the brightness of the LED by changing the amount of power supplied to it.

## Applications

- LED brightness control
- Smart lighting systems
- Home automation
- IoT projects
- Embedded systems

## Simulation

This project was created and tested using the Wokwi ESP32 Simulator.

### Wokwi Project

https://wokwi.com/projects/476330846437582849
