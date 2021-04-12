# comal80
COMAL 80 for C64
https://carmony.xyz/10-commodore/commodore-64-projects/2-comal-80-for-the-c64.html

In December of 2020 I was asked by KEN SIMMONS to create a comal-80 cartridge, for the Commodore 64, from an old COMAL TODAY magazine schematic. The COMAL80 cartridge uses unique 'bankswithcing' to switch up to 96KB of ROM.

This project is a result of that task. 

The board is a simple 2 layer design, with (3) 27C256 EPROMS, and (3) logic devices (74LS86, 74LS161, 74LS139), others may be substitued but are not known at this time.

The gerber files for creating a PCB are located in the gerbers directory. The bin files for U1 and U2 are located in the bin folder. U3 is left empty, and is used for personal space (if needed) for user applications, called packages. There is a 'superchip' that existed to allow for expansion of the COMAL 80 system, however I cannot locate this bin currently.

1-18-2021	GutHub creation and release of V1. Design is known working and completed. No known issues or releases planned. 

1-19-2021 C64/C128 folders added. C128 Comal Cartridge schematic added.
