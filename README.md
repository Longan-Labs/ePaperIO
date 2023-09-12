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

The 2.13 inch ePaper Breakout Board is a specialized expansion board designed for seamless integration with Seeed Studio's XIAO development board and Raspberry Pi. This board offers a highly flexible and convenient way to incorporate ePaper display capabilities into a wide range of projects, from smart homes to industrial control systems and educational applications. The board comes equipped with a XIAO socket, a 40-pin header for Raspberry Pi, a 4-pin Grove connector, and a user button, providing multiple options for connectivity and control.

**Note**: This expansion board **does not include** a 2.13-inch ePaper display; the display must be purchased separately.

## Features


## Specification


## Applications

- **Electronic Labels**: For use in stores or warehouses for long-lasting, low-power information display on product labels.
- **Information Boards**: Suitable for public transport or conference rooms, providing long-term static information display.
- **Portable Devices**: Such as e-readers or outdoor navigation devices that require long-lasting information display without consuming much power.
- **Energy-Efficient Projects**: Suitable for any applications requiring low power consumption and long-lasting information retention.

## Hardware Overview

This section provides a detailed overview of the various components and interfaces on the 2.13 inch ePaper Breakout Board.

![](https://raw.githubusercontent.com/Longan-Labs/ePaper213/main/images/hw.jpg)

- **2. 20-pin FPC Conncctor**: For the 2.13 inch ePaper.
- **3. User Button**: For implementing various custom functions.
- **4. 4-pin Grove Connector**: For connecting other Grove modules or devices.
- **5. XIAO Socket**: For connecting the Seeed Studio XIAO development board.

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

<div className="altium-ecad-viewer" data-project-src="https://github.com/Longan-Labs/ePaper213/raw/main/epaper213.zip" style={{borderRadius: '0px 0px 4px 4px', height: 500, borderStyle: 'solid', borderWidth: 1, borderColor: 'rgb(241, 241, 241)', overflow: 'hidden', maxWidth: 1280, maxHeight: 700, boxSizing: 'border-box'}}>
</div>


## Resources

- **[Zip]** [Eagle file](https://github.com/Longan-Labs/ePaper213/raw/main/epaper213.zip)
- **[Github]** [Demo Code](https://github.com/Longan-Labs/ePaper_213TestCode)
- **[PDF]** [Datasheet - ssd1680](https://github.com/Longan-Labs/ePaper213/blob/main/SSD1680.pdf)
- **[PDF]** [Datasheet - GDEY0213B74](https://github.com/Longan-Labs/ePaper213/blob/main/GDEY0213B74.pdf)

## Tech Support
If you have any technical issue.  submit the issue into our [forum](https://forum.seeedstudio.com/).