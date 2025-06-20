# AMSTRAD GX4000 / CPC464+ MULTICART
32 IN 1 SMD

This cartridge allows programs to run on the Amstrad GX4000 or CPC464+ computer

It uses two MX29F1610 ROMs to store up to 16 programs of 128kb each.

With the switch on top of the cartridge it is possible to select which rom to use, while with the dipswitch the bank is selected from 0 to 15, for a total of 32 games.

Amstrad uses a protection system for these cartridges, you can use the original chip **acid** (taken from another cartridge) or a 74HC112N flip-flop.

PCB:

![alt text](https://github.com/zeus074/Amstrad-GX4000-Multicart-32-in-1/blob/main/IMG/pcb_top.jpg)
![alt text](https://github.com/zeus074/Amstrad-GX4000-Multicart-32-in-1/blob/main/IMG/pcb_bottom.jpg)

:coffee: if you want the PCB, please support me and follow this link : <a href="https://www.pcbway.com/project/shareproject/Amstrad_GX4000_multicart_or_CPC464_32in_1_SMD_3feb920f.html" target="_NEW">PCBWAY!</a>


You can find the video of this project on the Retrofixer channel: link

Please consider subscribing to the channel, it's free and helps us to improve and always offer you new videos and more!


**Components:**

R3,R4,R1,R2,R8,R9,R10,R11,R5: 10K (1206)

R6,R7: 4K7 (1206)

C5,C3,C4,C2,C1: .1uF (1206)

C1,C2,C3,C4: 100nF ceramic

U1,U2: MX29F1610MC-10 (SOP44)

Mount Amstrad 40908 (U4) or the 74HC112N (U3) "Do not use them together!"

DP1: Dip-switch (4pin)

SW1: Slide switch 2 position (DPDT)

*Resistors r10 or r11 can not be mounted if the respective inputs A17 or A18 are used by the console and not managed by the dipswitch


**Realization:**

the gx4000 has a system to prevent the insertion of the cartridge with the console on and removal, it is necessary that the flaps of the slot are all open otherwise the switch remains blocked. 

To overcome this you can enlarge them by hand or make a case for the cartridge, if you make the case, the chips must be soldered on the pcb without a socket, otherwise the card will be too thick.

Behind the card there are 2 jumpers JP17 and JP18 which can be closed in position SW or A17,A18.

If they are to be used for 128k games, they must be set to SW, so 16 games can be managed in the dipswitch.

If you use larger roms these can be managed by the console by making the jumper between the central pin and the relative input.

This change (JP17,JP18) affects both roms.

You can find schemnatic and BOM in the relative folders.

**Final cartridge:**

![alt text](https://github.com/zeus074/Amstrad-GX4000-Multicart-32-in-1/blob/main/IMG/IMG_3454.jpg)

Ofcourse! This case is in the 3D_Print folder.

Subscribe to my channel Retrofixer https://www.youtube.com/@retrofixer to keep us going in this work.

You can print ready-made pcb on PCBWAY! https://www.pcbway.com/project/shareproject/Amstrad_GX4000_multicart_or_CPC464_32in_1_SMD_3feb920f.html


Enjoy!
