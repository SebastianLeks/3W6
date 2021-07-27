![3w6](https://raw.githubusercontent.com/weteor/3W6/main/images/3w6_1s.jpg) 

# 3w6 - split ortholinear keyboard

The 3w6 is a low profile, split ortholinear keyboard with 36 keys.

I needed a keyboard for work and wasn't really satisfied with the available alternatives (namely Corne, Kyria and Ferris), mostly because they were rather large and didn't had the spacing I would like.

It's designed to be a no frills, cheap and small keyboard to be taken everywhere.

So no hotswap, no multiple switchtypes, no encoders, no LEDs.

BUT with onboard controllers (so no extra ProMicros, Elite-C), production files including SMT assembly files, and sturdy through hole mounted USB-C connectors.

## currently testing / prototyping revision 2
changes:
- new middle plate (1.6mm, better 2.0mm) instead of diodes. Uses Aluminium PCBs as a cheaper alternative to lasered aluminium. 
- pimoroni trackball support (can only be used combined with the new middle plate when used with the plate)
- plate is now 1.2mm thick, to fit the chocs better. Needs middle plate, since the cutouts of the USB-Connectors were left out. There is enough space for them under the plate, when the middle plate is in place.
- added mounting holes to support tenting puck from splitkb.com. Due to insufficient space not all 4 holes are supported, but 3 screws should be enough to hold everything comfortably in position. Can only be used plateless! 
- package for the MCU was changed from QFN32 to TQFP32, since the previous one wasn't available. Can now be soldered/replaced by hand if need.
- IO-expander was changed from TCA9555 to TCA9535, since the previous one wasn't available. Package changed from WQFN24 to TSSOP24. Can now be soldered/replaced by hand if need.
- Board can now be soldered by hand if needed (challenging though, 0402 components). 
## try it
You can print [this file](https://raw.githubusercontent.com/weteor/3W6/main/plate_outline.pdf) to test if you like the layout. Or mount it to some cardboard and test it with your favourite switches.

## build instructions
you may find instructions here: [build instructions](./prod/build_instruction.md)

##

![3w6](https://raw.githubusercontent.com/weteor/3W6/main/3w6_2s.jpg)
![3w6](https://raw.githubusercontent.com/weteor/3W6/main/3w6_3s.jpg)
