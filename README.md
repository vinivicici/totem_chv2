# TOTEM PCB FILES
## Note for Choc V2
This repository contains TOTEM PCB files compatible with Choc V2 switches.

### Main Changes
1. Changed socket to Choc V2 compatible
2. Removed soldering option (HOTSWAP ONLY)

### ⚠️ WARNING
Original TOTEM cases are not compatible with this PCB file.
Switch size is different (14.0mm vs 13.8mm), causing case dimension mismatch.
You need to modify original TOTEM cases with Fusion 360 or use PCB only.

## MANUFACTURING
Manufacturing method is same as original. 
If you want to get the PCB made you need to download the [ZIP](/PCB/totem_0-3/totem_chv2_gerbers.zip/) and upload it to the website of the manufacture 
I can recommend [JLCPCB](https://jlcpcb.com/), [Seeed Fusion](https://www.seeedstudio.com/fusion_pcb.html) or [PCBway](https://www.pcbway.com/).
If you want the silkscreen in yellow [AllPCB](https://www.allpcb.com/online_pcb_quote_new.html) is a pretty affordable choice.

- download [the ZIP file](/PCB/totem_0-3/totem_chv2_gerbers.zip/)
- upload the ZIP file to the website of the manufacturer.
- sometimes the Gerber preview from JLCPCB can't display the PCB, even when the files are fine. In this case use these dimensions: 258.7mm * 94.35mm
- PCB Thickness 1.6mm
- 2 layers
- PCB Qty as much as you like. One PCB is a full keyboard.
- PCB Color Black (or any other color you like)
- No impedance control
- Surface Finish HASL(with lead) if you want the easiest soldering experience or LeadFree HASL.
- Remove Order Number Yes

***

## CHECK PINOUT OR TRACES

If you only want to check the traces or see what is connected to which pin you can take a look at these graphics.
You can also take a look at the [schematics](TOTEM_0-3_schematics.pdf) and the [PCB](TOTEM_0-3_PCB.pdf) as PDF.

***

## TAKE A DEEPER LOOK OR MODIFY 

You can download the project if you need to take a deeper look or modify something. You need the Open Source software [KiCad](https://www.kicad.org/) to open it.
