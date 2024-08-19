<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The LUT can implement a binary function with three parameters.
For each possible combination of inputs, a d-flip-flop is storing the desired output.
To configure which function should be implemented, the table must be pushed into the scan chain.
After eight clock cycles, the configuration is done.

## How to test

Connect a clock, reset, switches and an LED as output.
Load the table by activating the clock first, then giving the wanted values to the scan chain head.
After the table is fully loaded, disable the clock and connect the inputs to test, if the design is following the desired lookup table.

## External hardware

Whatever hardware the LUT should be used with.
For testing, LEDs and switches should be enough.
