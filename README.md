# Microwave-Oven-Control-System
Embedded C Microwave Oven simulation using PIC16F877A with LCD, keypad, timer interrupts, and multiple cooking modes.
# Microwave Oven Control System using PIC16F877A

An Embedded C-based Microwave Oven Control System developed using the **PIC16F877A microcontroller**. The project simulates the working of a real microwave oven with multiple cooking modes, timer control, preheating, pause/resume functionality, and a user-friendly menu-driven interface using a Character LCD and Matrix Keypad.

---

## Overview

This project emulates the basic operations of a microwave oven by providing different cooking modes such as **Micro, Grill, and Convection**. Users can set cooking time, configure preheating temperature for convection mode, and control the cooking process using dedicated keypad inputs.

The system is designed using Embedded C and demonstrates peripheral interfacing, timer-based control, interrupt handling, and menu-driven application development.

---

## Features

- Power-up welcome screen
- Menu-driven interface
- Three cooking modes:
  - Micro Mode (900W)
  - Grill Mode
  - Convection Mode
- User-configurable cooking timer (MM:SS)
- Preheat temperature setting (up to 180°C)
- Countdown timer using Timer2 interrupt
- Start/Resume cooking
- Pause cooking
- Stop cooking
- Cooking completion indication using buzzer
- Fan control during cooking
- LCD-based user interaction
- Matrix keypad navigation

---

## Hardware Used

- PIC16F877A Microcontroller
- 16×2 Character LCD (CLCD)
- Matrix Keypad
- Buzzer
- Fan
- Timer2
- MPLAB Supported Development Board / PICSimLab

---

## Software Used

- MPLAB X IDE
- XC8 Compiler
- Embedded C
- PICSimLab

---

## Cooking Modes

### 🔹 Micro Mode
- 900W cooking mode
- User sets cooking time
- Countdown timer starts after confirmation

### 🔹 Grill Mode
- Timer-controlled grilling operation
- Supports pause, resume, and stop

### 🔹 Convection Mode
- User selects preheat temperature (25°C–180°C)
- One-minute preheating before cooking
- Timer-based cooking after preheating

---

## Keypad Controls

| Key | Function |
|-----|----------|
| 1 | Micro Mode |
| 2 | Grill Mode |
| 3 | Convection Mode |
| 4 | Start / Resume / Add 30 Seconds |
| 5 | Pause |
| 6 | Stop |
| * | Clear Input |
| # | Confirm |

---

## Working

1. System displays the power-up screen.
2. User selects a cooking mode.
3. Sets the cooking time.
4. In Convection mode, user sets the preheating temperature.
5. Cooking starts after confirmation.
6. Timer counts down using interrupts.
7. User can pause, resume, stop, or extend cooking time.
8. Buzzer indicates completion of cooking.

---

## Concepts Used

- Embedded C Programming
- PIC16F877A Programming
- Timer Interrupts
- Matrix Keypad Interfacing
- Character LCD Interfacing
- State Machine Design
- Countdown Timer
- Menu-driven User Interface
- Buzzer and Fan Control

---

## Learning Outcomes

- Timer interrupt programming
- Embedded user interface design
- State machine implementation
- Matrix keypad scanning
- LCD interfacing
- Countdown timer logic
- Real-time embedded application development

---

## Future Enhancements

- Automatic cooking presets
- Temperature sensor integration
- Door open/close detection
- EEPROM for storing favorite settings
- RTC-based delayed cooking
- Touch keypad interface

---
