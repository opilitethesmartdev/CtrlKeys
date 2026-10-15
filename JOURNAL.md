---
title: "CtrlKeys"
github: "https://github.com/opilitethesmartdev/CtrlKeys"
description: "Portable USB Keypad with Bluetooth support, meant for control in the background"
created_at: "2026-10-15"
total_time: "1h 18m"
---

# October 15, 2026: Basic Schematic
<!-- fabricate:entry 463 -->

I wired the basic schematic of the project, meaning the USB port, the ESP32S3 SoM, the switches and the LEDs. 
![](https://fabricate.hackclub-assets.com/76f6446bfb4ef5b7e3d0ca416ca41c67747a3f036f2649df4e4b77ef5b80577d/image-png/image.png)
I added a debug header (UART) and a level shifter (SN74LVC1T45) for the WS2812Bs. I still have to do the battery setup, and then the software, but i'll manage. I'm using a Diodes AP63203 StepDown for the voltage, idk just wanted to maybe not use a common linear regulator and put some more numbers on my *electricity bill*.

Timelapse: https://lapse.hackclub.com/timelapse/DImM2FlCJ2KP

**Total time spent: 1h 18m**
