# Medusa-Toolhead
**__IN BETA__**
![FrontView](/img/frontview.png)

EVA 2.4 replacement for the [**SnakeOil-XY CoreXY 3D Printer**](https://github.com/ChipCE/SnakeOil-XY).

Designed to need the least hardware possible while still being stiff and light.

3 printed parts total if you are using the BlTouch probe.

## Tensioning Idlers
Belt mounting on the toolhead itself is very simplified to save weight. You will need to print the tensioning front idlers and replace the static stock ones. This will allow you to tension the belts.

	-2x M5x40mm Button Head (Idler shaft)
	-2x M5 Standard Nut (Idler shaft)
	-4x M6x8mm (Mouting the idlers to the frame - Reuse the ones used to hold the old ones in place)
	-2x M3x30mm Button Head (Tensioning Screw)
## Toolhead

### Currently supports:

	Extruder:
	-Sherpa Mini Extruder
	
	Hotend:
	- Dragon SF and HF
	- Mosquito or NF-Crazy
	
	Probe:
	- BlTouch
	- Klicky Probe
	
### Cooling 
Uses a modified [Eva](https://github.com/EVA-3D/eva-main) cooling duct.

### Klicky Probe
 Currently supports [Klicky probe](https://github.com/jlas1/Klicky-Probe) with a custom toolhead mount and dock mount.

Toolhead Mount            |  Dock & Mount
:-------------------------:|:-------------------------:
![backview_klicky](/img/backview_klicky.png)  |  ![mount_klicky](/img/mountview_klicky.png)

### Toolhead BOM: 

	- 3010 Fan for hotend cooling.
	- 5015 Fan for part cooling
	- 5x M3-12mm Screw (Hotend Cooling Fan, Shroud, Cooling Duct)
	- 3x M3-20mm Screw (Cooling Duct and Fan) 
	- Mounting hardware that goes with your hotend (Usually 2 or 4 M2.5 screws)
	- 2x M2x10mm Screw (Endstop mounting)
	
	AND
	
	- Bltouch
		- 3x M3-10mm Screw
		- 1x M3-12mm Screw
		- 2x M3 Nut
		
			OR
			
	- Klicky
		- 2x M3-6mm Screw
		- 2x M3-16 Screws
		- 2x M2-10 self tapping screws
		- 1x Omron D2F Microswitch or similar
		- 8x 6x3mm round magnets
		
		

	
