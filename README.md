
# Unextended keyboard

Welcome to the **Unextended Keyboard** project. The goal of the project is to make a ZMK powered wireless 60% keyboard that targets ALPS switches and specifically the keycaps from Apple Extended Keyboards.

## Disclaimer:
I am not a case designer, this is just a personal project for me to play with 3D CAD. There are likely many best practices that are missing in this project and there are likely many improvements that can be made for better machinability. See this as a work in progress or something to get inspiration from, rather than something production ready.

## Status:
A prototype has been made of the current step model. The PCBs in this repo are currently untested. For the prototype, a cyber60 PCB with the USB-port removed was used. The PCBs share the same pinout and basic functions as the Cyber60 Revision C/D, so the same code can be used for firmware and bootloader if needed. For a QMK based keyboard build, the Waffling60 alps PCB can be used with the USB port removed. PCBs available here: https://4pplet.com/products/waffling60

## Keyboard Parts:
- Case
- PCB + C1 or C3 compatible daughterboard
- 3.7v single cell lipo/liion battery with a 2-pin JST PH connector (check polarity on PCB)
- Plate
- Cover plate for battery and daughterboard
- M2 screws for daughter board and cover plate
- Alps switches, stabs and AEK-keycaps

## Todo:
- Make releases for PCB and plates
- Verify PCB designs
- Overhaul the general design for better machinability.

# Layout support ANSI:
![alt text](./readme-images/layout_support_ANSI.jpg "Layout support ANSI")
# Layout support ISO:
![alt text](./readme-images/layout_support_ISO.jpg "Layout support ISO")

## Comments on plates:
I have made three different plate designs
- OG ANSI layout
- OG ISO layout
- ANSI layout with split r-shift, split space and split backspace (this is what I'm personally using)

## Revisions:
- V1: Second prototype of the case

## Pics of initial proto:
![alt text](./readme-images/initial_proto_1.jpg "Initial proto 1")
![alt text](./readme-images/initial_proto_2.jpg "Initial proto 2")

<a href='https://ko-fi.com/4pplet' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' />
