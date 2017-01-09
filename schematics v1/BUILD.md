#Build instructions
Build the PCB as usual using the [BOM](https://github.com/tommueller/UM-TSS/blob/master/schematics%20v1/BOM.ods?raw=true) **BUT** do not add caps: **C5, C7, C9, C12 and C13**. You can doublecheck with this image: ![](https://github.com/tommueller/UM-TSS/blob/master/schematics%20v1/pcb%20v1%20populated%20front.JPG?raw=true)

When you are finished with this, you need to do the following to get this up and running:

- at the back of the PCB solder a 8.2nF cap between the legs 1 & 7 of U4 and U5 each
- solder a 100nF cap between the legs 1 & 7 of U3
- add a little wire between pins 2 & 13 of U3
- take C9 (10uF) and solder it with its positive side to pin 12 of U3 and the negative side to the negative pad of C9

Again you can doublecheck with this image: ![](https://raw.githubusercontent.com/tommueller/UM-TSS/master/schematics%20v1/pcb%20v1%20populated%20back.JPG)
