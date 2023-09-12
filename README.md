---
description: TBD
title: TBD
keywords:
- XIAO
image: TBD
slug: EPAPER IO BREAK OUT BOARD
last_update:
  date: 9-8-2023
  author: Stephen Lo
---

<p style={{textAlign: 'center'}}><img src="https://raw.githubusercontent.com/Longan-Labs/ePaperIO/main/images/4-105990172-ePaper-Breakout-Board-45back.jpg" alt="pir" width={600} height="auto" /></p>

Meet the ePaper Breakout Board, your go-to solution for driving ePaper displays effortlessly. Designed with a 20-pin FPC connector, this board provides a seamless link to your ePaper. But that's not all! With an onboard XIAO socket, you can harness the power of XIAO as the processor to control your ePaper. And if you're looking to expand your options, the 8-pin 2.54 Header allows you to easily integrate any microcontroller of your choice. Think of this board as your ePaper's "Best Friend Forever," enhancing its capabilities and making your life easier.

**Note**: This breakout board **does not include** an ePaper display; the display must be purchased separately.

## Features

- **20-pin FPC Connector**: Provides a robust and reliable connection to ePaper displays.
- **XIAO Socket**: Allows you to use XIAO as the processor, offering a compact yet powerful control solution.
- **8-pin 2.54 Header**: Offers flexibility by letting you connect to any microcontroller, opening up a world of possibilities.
- **Plug-and-Play**: Designed for ease of use, making it perfect for both beginners and experts.
- **Versatile Applications**: Suitable for a wide range of ePaper displays, from small to large sizes.

## Applications

- **Digital Signage**: Use the ePaper Breakout Board to create dynamic and energy-efficient digital signs.
- **E-Readers**: Build your own customized e-reader with features tailored to your needs.
- **Smart Home Control Panels**: Integrate the board into a smart home system for a sleek and modern control panel.
- **Retail Price Tags**: Create electronic price tags for a more efficient and eco-friendly retail experience.
- **Educational Tools**: Develop interactive educational materials that can be easily updated and are energy-efficient.

## Hardware Overview

This section provides a detailed overview of the various components and interfaces on the ePaper Breakout Board.

![](https://raw.githubusercontent.com/Longan-Labs/ePaperIO/main/images/hw.png)

- **1. 20-pin FPC Conncctor**: For the 2.13 inch ePaper.
- **2. XIAO Socket**: For connecting the Seeed Studio XIAO development board.
- **3. IO Break out**: For connecting the others controller, such Arduino UNO or Raspberry Pi.

### Pin Defines

|ePaper|XIAO|
|------|----|
|RST|D0|
|CS|D1|
|DC|D3|
|BUSY|D5|
|SCK|D8|
|MOSI|D10|

## Getting Started with Arduino

Welcome to the quick start guide for the 2.13 inch ePaper Breakout Board. This guide aims to help you set up and get started with your new 2.13 inch ePaper Breakout Board in conjunction with the XIAO ESP32 C3 main controller.

1. **Insert XIAO ESP32 C3**: Insert the XIAO ESP32 C3 into the socket on the expansion board.
2. **Connect 2.13-inch ePaper Display**: Insert the 2.13-inch ePaper display into the FPC connector designated for the screen.
3. **Download Test Code**: Download the [test code](https://github.com/Longan-Labs/ePaper_213TestCode) onto the XIAO ESP32 C3 processor.
4. **Run and Observe**: After successfully downloading the code, you should see some logos displayed on the ePaper screen.


## Schematic Online Viewer

<div className="altium-ecad-viewer" data-project-src="https://github.com/Longan-Labs/ePaperIO/raw/main/epaperIO.zip" style={{borderRadius: '0px 0px 4px 4px', height: 500, borderStyle: 'solid', borderWidth: 1, borderColor: 'rgb(241, 241, 241)', overflow: 'hidden', maxWidth: 1280, maxHeight: 700, boxSizing: 'border-box'}}>
</div>


## Resources

- **[Zip]** [Eagle file](https://github.com/Longan-Labs/ePaperIO/raw/main/epaperIO.zip)

## Tech Support
If you have any technical issue.  submit the issue into our [forum](https://forum.seeedstudio.com/).