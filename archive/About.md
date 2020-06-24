####  What is all this for?  Here are some words from founding scientist @gregsgit :

<p>

"We use the FPGA to prototype / emulate a "Soft Core" CPU with and without Dover's IP (logic) called CoreGuard.
An FPGA can simulate (sometimes called "emulate") logical circuits, and is reprogrammable. So you can design circuitry that eventually will be fabricated in silicon, but you can work out bugs and try different designs using the FPGA "fabric".

For demos, we synthesize to the Xilinx FPGA: a design for a RISC-V CPU, a simple UART (serial interface), an interface to the on-board DDR memory and flash memory, and a simple video output. We put some software in the on-board flash, then boot a working RISC-V system. We'll show how the software can be attacked, using I/O over the serial port to mimic what would typically take place over a network connection. Next, we show the same SoC (CPU + UART + memory) with CoreGuard logic added in. We run the same software and then show that the same attack is blocked by CoreGuard.

We also use the FPGA to emulate the Arm CPU that we are interfacing with for our NXP customer."

</p>
