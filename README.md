# 345ToWire
This project helps you use your old Ademco 5800 alarm sensors without an Ademco panel!

-- To start off, I would like to give credit to https://github.com/Dilbert66/esphome-vistaECP for all of the logic for the wireless receiver, it would not be possible without the work from thus project.

## Part I, Overview

-- This project was created to let you use Ademco 5800 wireless 345mhz alarm sensors without an Ademco system. The reason why I created this project is because I wanted to use some Ademco 5808 smoke detectors on a Fire Lite MS5210UD. 

-- Compared to vistaECP project, this one adds a web UI, GPIO triggers, sensor management, and multiple types of API.

DISCLAIMER: THIS PROJECT IS NOT MEANT TO BE USED FOR UL INSTALLATIONS, I AM NOT LIABLE FOR ANY DAMAGES CAUSED BY THE USE OF THIS PROJECT.

## Part II, Components Needed

-- 1x ESP32 Devkit V1 (Others may work too, but this is the only one I tested it on)

-- 1x CC1101 315/433 MHZ SPI Radio Transceiver Module

## Part III, Assembly and Software

-- Uses the default ESP32 Devkit V1 Pinout for CC1101/SPI so stop being lazy and figure it out yourself, no diagram here.

-- Just flash the .ino file to your board, not so hard.

-- This will create a wifi ap you need to connect to, the password is 345towire.

-- Web interface password is admin/admin by default.

Okay I guess that's it, if anyone has any issues do not hesitate to create an issue request, I will try to respond as fast as possible. Have a great day!!
