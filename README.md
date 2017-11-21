# UM-TSS - CMOS Drumsynth
This is a circuit by Jacob Watters ([check the original block post](http://www.jacobwatters.com/blog/um-tss-drum-machine/)), I just did the PCB-layout. In agreement with Jacob this is released here as open hardware. Hopefully you enjoy the project and maybe you can even improve it!

## The circuit
The circuit is based around a couple of 40106 hex-schmitt triggers. I removed the divider from Jacobs layout to make every sound triggerable by itself. The trigger ins are protected by clamping diodes.

## PCB v1
PCB v1 has a couple of bugs (mainly because I used the wrong revision of Jacobs circuit **duh**). But the PCB can certainly be used to build a running circuit. Check the build guide for PCB rev. 1 [here](https://github.com/tommueller/UM-TSS/blob/master/schematics%20v1/BUILD.md) and the [BOM](https://github.com/tommueller/UM-TSS/blob/master/schematics%20v1/BOM.ods?raw=true)

## PCB v2
I already fixed most of the issued in the schematics for version 2. I hope that together we can make a second version of the PCB that runs more smooth!

## Case
I created a case which can be fabbed by a lasercutter. The SVG is available in the repo. The plans are for 3mm material! Here is an image of the first finished prototype (3mm colored HDF): ![UM-TSS first prototype](https://raw.githubusercontent.com/tommueller/UM-TSS/master/front-on.JPG)
