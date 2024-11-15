Components for a zmk dongle: a reversible pcb that features mounting holes and wiring for a reset button, and a 3D printed case. The pcb is reversible so that you have the option to mount a reset button to the left or right side of the usb port.

## Files:
- gerbers for a promicro compatible reversible pcb
- 3D models for a case
- ergogen code used to generate the pcb

## Bill of materials:
- 4 M2 screws (5-6mm length)
- 4 M2 heatset inserts (any length <5mm will work)
- Panasonic EVQ-PU[A|C|J|L]02K (side-operated momentary switch)
- microcontroller with promicro footprint
- sockets for the mcu or headers that came with the mcu

## Assembly notes:
- PCB design is intended for the mcu to be mounted face down, such that the RAW pin is in the top left corner. 
- Solder the jumper pads on the same side of the pcb that the mcu is mounted to.

![1](https://raw.githubusercontent.com/dohn-joh/dongle-zmk/master/photos/1.jpg)
![2](https://raw.githubusercontent.com/dohn-joh/dongle-zmk/master/photos/2.jpg)
![3](https://raw.githubusercontent.com/dohn-joh/dongle-zmk/master/photos/3.jpg)
![4](https://raw.githubusercontent.com/dohn-joh/dongle-zmk/master/photos/4.jpg)
![5](https://raw.githubusercontent.com/dohn-joh/dongle-zmk/master/photos/5.jpg)

This small project was inspired by https://github.com/spe2/zmk_dongle_hardware.
I used ergogen to generate the pcb and designed the case in fusion360.
