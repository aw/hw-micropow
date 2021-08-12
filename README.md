# μPow: 3D printer buck converter for 12V/5V fans

A dual-output switching DC-DC buck converter to replace the 24V fans on a 3D printer.

![3d-board-top](https://user-images.githubusercontent.com/153401/128290882-a67b1865-129f-48a1-b85f-4ca187384cda.png)
![3d-board-pcb](https://user-images.githubusercontent.com/153401/128291809-89f22b01-c862-4819-b162-b3a2a67d089a.png)

This project is also described in detail [on Hackaday.io](https://hackaday.io/project/179566-pow-3d-printer-buck-converter-for-12v5v-fans)

This project is [certified open hardware](https://certification.oshwa.org/jp000010.html):

[![OSHW_mark_JP000010](https://user-images.githubusercontent.com/153401/129276256-2371ccca-7161-45c1-a8f6-f861aa9da215.png)](https://certification.oshwa.org/jp000010.html)

# How it works

The left side of the PCB accepts 8V to 28V DC input. It then converts the input voltage to 12V and then to 5V.

The output voltages are accessible on the right side of the PCB and can be used to power 12V or 5V fans or other devices.

# PCB features

  * Form factor 44mm x 22mm
  * PCB traces are 1mm and should handle at least 1.5A of current
  * Open Source Hardware under [CC BY-SA 4.0](#License)
  * On-board (SMD) capacitors, fuses, and diodes
  * Simple passive design draws 0mA current when no devices are connected
  * Thermal vias in strategic locations

# BOM (through-hole)

| Quantity | Item and Description |
| :----: | :---- |
| 1 | XPPower VR10S05 SIP3 5V 500mA DC-DC switching regulator |
| 1 | XPPower VR10S12 SIP3 12V 500mA DC-DC switching regulator |
| 3 | 3-pin JST-XH male connectors |

# BOM (surface mount)

| Quantity | Item and Description |
| :----: | :---- |
| 1 | 10uF 50V Capacitor 5x5.3mm |
| 2 | 22uF 16V Capacitors 5x5.3mm |
| 1 | 40V 1A Diode SOD-123 |
| 2 | 28V 1A Diode SOD-123 |
| 1 | 33V 1.1A/2.2A Polyfuse 1812 |

# Schematic

The schematic is available [here](schematic-v1.pdf)

# Notes

This PCB was designed with [Kicad](https://kicad.org/) v5.1.9 from the `debian buster-backports` repository.

I take no responsibility for any problems that may occur with your use of this PCB or design files. Create and use at your own risk.

# License

μPow: 3D printer buck converter for 12V/5V fans © 2021 by [Alexander Williams](https://a1w.ca/) is licensed under [_CC BY-SA 4.0_ (Attribution-ShareAlike 4.0 International)](https://creativecommons.org/licenses/by-sa/4.0/).
