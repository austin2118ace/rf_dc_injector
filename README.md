# RF DC Injector

This repository hosts a simple PCB for a RF DC injector/extractor for use in HAM radio applications.

## Brief Description
DC can be co-located on a RF feed line to power remote hardware with only two of these boards. On the injector side, the DC power supply is protected from the RF with a bank of inductors, and the RF power source is isolated from the DC using a capacitor.
On the "extractor" side, the same board is used in the reverse configuration. The antenna is isolated from the DC using the capacitor, and the remote DC power rail is isolated from RF using the inductors.

## Manufacturing
I had several of these boards manufactured at Oshpark but JLCPCB/PCBWay are both valid options. There are two pads for coax connections; I used two lengths of RG316. For the DC power input/output, there is a footprint for a standard DC power jack.
Choose value(s) of capacitance and inductance that make sense for your application.

## Compatability
This project was created using KiCad v10 and includes a custom footprint that you will need to ensure is correctly loaded. 

Good luck and 73!
KQ4TYW
