# CRASM

CRASM is a portable cross-assembler for the 6800, 6801, 6803, 6502, 65C02, and Z80.

## Documentation

See the file [crasm.html](http://htmlpreview.github.io/?https://github.com/colinbourassa/crasm/blob/master/crasm.html).

## Changelog

   *  crasm-1.8:  
      Fixed incorrect 6800 opcode for BLE  
      Fixed inconsistent handling of signedness for program counter variable  

   *  crasm-1.7:  
      Fixed handling of extended ASCII characters in input files (Windows-specific)  
      Fixed uninitialized memory in label array (was sometimes causing "too far branch" errors)

   *  crasm-1.6:  
      Fixed mishandled SUBD immediate (6801/6803)  
      Fixed incorrect opcodes for MUL and RTI (6801/6803)  
      Fixed documentation for DS pseudo  
      Updated version number in page headers on output  
