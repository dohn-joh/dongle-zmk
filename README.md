This repo contains:
- gerbers for a promicro compatible reversible pcb
- 3D models for a case
- ergogen code used to generate the pcb

What is the purpose of this?

To create a reversible pcb that offers mounting holes, wiring for a reset button, and files for a protective case. The pcb is reversible so that you have the option to either mount the reset button to the left or right side of the usb port.

Bill of materials:
- 4 M2 screws (5-6mm length)
- 4 M2 heatset inserts (any length <5mm will work)
- Panasonic EVQ-PU[A|C|J|L]02K (side-operated momentary switch)
- microcontroller with promicro footprint
- sockets for the mcu or headers that came with the mcu

Assembly notes:
- This design is intended to orient the mcu face down, such that the RAW pin is in the top left corner. 
- Solder the jumper pads on the same side of the pcb that the mcu is mounted to.


This small project was inspired by falkenad's designs for pcbs to be used with various nrf mcus and oled screens.
I used ergogen to generate the pcb and designed the case in fusion360.
