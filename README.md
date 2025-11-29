# Plant Monitoring System using LPC2148

## Overview

This repository contains the code for a plant monitoring and data logging system built around the LPC2148 microcontroller and simulated in Proteus.  
The system monitors key environmental parameters and logs them to an SD card for later analysis.

## Features

1. Soil moisture sensor for monitoring soil water content  
2. LDR module for sensing greenhouse interior light levels  
3. Temperature measurement and basic temperature control logic  
4. SD card module for logging sensor data

## Dependencies

For the code to work as intended, you must:

- Create an LPC2148 project in your preferred IDE (for example, Keil µVision).  
- Add and configure the FatFs library from:  
  https://elm-chan.org/fsw/ff/  

Make sure the FatFs source files and configuration files are correctly included in your project so that SD card access and file system operations function properly.

- Check the Video to create a virtual image file using Winimage to include it in the sd card module 
