# Printing Notes

Some rough notes on the design and printing of these files. If you are trying to print this tank yourself, you might find these useful.

I have included in this repository the G-code used, mostly for my own convenience. Of course, you should use a slicer to create files tailored for your printer.

## Design Philosophy

I am not an expert at either CAD or 3D printing. If something works, I go with it. Which is to say, the designs herein are not necesarily refined.

Generally I have favored functionality over form. Most of the parts are printed upside-down, with the functional parts facing upward.

I am lazy and do not enjoy post-print cleanup. So my designs are oriented toward minimizing that, using a brim or no bed adhesion and as little support as possible.

I haven't been consistent with infill percentage but generally use 15-20% on most parts. Mechanical parts like gears get more infill.

## Printer Setup

I use a close-to-stock Creality Ender 5. I have been printing with PLA but I'd like to try using PETG. I recently purchased a filament dehydrator and I think this really helps with stringing.

My workflow is to create a design in FreeCAD, export to an .obj file, and use Cura to slice.

## Notes on Printing Individual Parts

### Chassis

* infill percentage: 15%
* build plate adhesion type: brim

### Hull

* infill percentage: 15%
* build plate adhesion type: brim
* support placement: touching buildplate
* support overhang angle: 80°

### Turret

* infill percentage: 20%
* build plate adhesion type: brim
* support placement: everywhere
* support overhang angle: 80°

### Turret Barrel

* infill percentage: 50%
* build plate adhesion type: none
* support: none

### Turret Base

* infill percentage: 20%
* build plate adhesion type: none
* support: none

## Turret Mast

* infill percentage: 30%
* build plate adhesion type: brim
* support: none
