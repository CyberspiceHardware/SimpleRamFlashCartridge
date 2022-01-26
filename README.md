# Simple Ram Flash Cartridge 

This is a simple ROM/RAM/Flash cartridge for a BBC Master or Acorn Electron.

It takes a single 32K memory device. For example an AS6C62256 or a AT28C256.

# Jumpers / Links

There are three jumpers

J2 - This selects whether the cartridge is for the Master or Electron. It selects the R/WR source from the edge connector.
J3 - This selects whether pin 27 is A14 or nWE. It is typically A14 for (E(P))ROM but nWE for SRAM or Flash.
J4 - This selects whether pin 1 is A14 or 5V. It is typically A14 for SRAM or Flash and 5V (VPP) for (E(P))ROM

You may omit J3 if you want to use a 27C128 EPROM chip where pin 27 is the nPGM pin.

