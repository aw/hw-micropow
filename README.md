# μPow: 3D printer buck converter for 12V/5V fans

A dual-output switching DC-DC buck converter to replace the 24V fans on a 3D printer.

![3d-board-top](https://user-images.githubusercontent.com/153401/128290882-a67b1865-129f-48a1-b85f-4ca187384cda.png)
![3d-board-pcb](https://user-images.githubusercontent.com/153401/128291809-89f22b01-c862-4819-b162-b3a2a67d089a.png)

This project is also described in detail [on Hackaday.io](https://hackaday.io/project/179566-pow-3d-printer-buck-converter-for-12v5v-fans)

# How it works

The left side of the PCB accepts 8V to 28V DC input. It then converts the input voltage to 12V and then to 5V.

The output voltages are accessible on the right of the PCB, and can be used to power 12V or 5V fans or other devices.

# PCB features

  * Form factor 44mm x 22mm
  * PCB traces are 1mm and should handle at least 1.5A of current
  * Open Source Hardware under [CC BY-NC-SA 4.0](#License)
  * On-board (SMD) capacitors, fuses, and diodes
  * Simple passive design draws 0mA current when no devices are connected
  * Thermal vias in strategic locations

# BOM

TODO

# Schematic

The schematic is available [here](schematic-v1.pdf)

# License

μPow: 3D printer buck converter for 12V/5V fans © 2021 by [Alexander Williams](https://a1w.ca/) is licensed under [_CC BY-NC-SA 4.0_ (Attribution-NonCommercial-ShareAlike 4.0 International)](https://creativecommons.org/licenses/by-nc-sa/4.0/).
