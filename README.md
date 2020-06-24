

|![Alt text](V5_A.png?raw=true)|![Alt text](V6_B.png?raw=true)|
|---|---|



A stylish demo enclosure for the Xilinx / Digilent Genesys 2 with a display panel.  

Check out what Dover Microsystems is up to here:
https://www.dovermicrosystems.com/

Prototyping & production @ the D&M Makerspace- see what else we're up to:
https://makerspace.plymouthcreate.net/


### Electronics:

<br>

**FPGA-  [Digilent Xilinx Genesys 2 FPGA Reference](https://reference.digilentinc.com/reference/programmable-logic/genesys-2/reference-manual)**


**The display and HDMI driver board from pimoroni-**  
[*The sketch for panel dimensions are shared over here too*](https://forums.pimoroni.com/t/cad-file-for-hdmi-8-ips-lcd-screen-kit-1024x768/12499/3?u=jesssullivan)



#### BOM for version 6:

 [*You can find the V6 interactive Fusion 360 model over here*](https://a360.co/36RBUQ1)    
    
 [*...additional V6 svg, stl layouts on tinkercad*](https://www.tinkercad.com/things/6H87w83xGPq)

*Materials:*

|Size   |Type|
|---    |--- |
|12"x12"|1/4" (6.35mm) clear acrylic sheet      |
|12"x12"| 3mm clear acrylic sheet               |
|12"x12"| 3mm colored acrylic sheet             |
|~45 grams| printer plastic (filament or resin) |


*Hardware:*

|Qty| Size |
|---| ---  |
|3  |m3x8  |   
|3  |m3x18 |
|1  |m3x20 |
|7  |m3 nut|
|2  |m2x14 |
|2  |m2x10 |
|4  |m2 nut|

<br>

####  What is this thing?  Some words from founding scientist @gregsgit:

<p>

*"We use the FPGA to prototype / emulate a "Soft Core" CPU with and without Dover's IP (logic) called CoreGuard.
An FPGA can simulate (sometimes called "emulate") logical circuits, and is reprogrammable. So you can design circuitry that eventually will be fabricated in silicon, but you can work out bugs and try different designs using the FPGA "fabric".

For demos, we synthesize to the Xilinx FPGA: a design for a RISC-V CPU, a simple UART (serial interface), an interface to the on-board DDR memory and flash memory, and a simple video output. We put some software in the on-board flash, then boot a working RISC-V system. We'll show how the software can be attacked, using I/O over the serial port to mimic what would typically take place over a network connection. Next, we show the same SoC (CPU + UART + memory) with CoreGuard logic added in. We run the same software and then show that the same attack is blocked by CoreGuard.

We also use the FPGA to emulate the Arm CPU that we are interfacing with for our NXP customer."*

</p>

![Alt text](LaserCuts.gif?raw=true)|
