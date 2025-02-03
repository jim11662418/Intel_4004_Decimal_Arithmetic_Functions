# Intel 4004 Decimal Arithmetic Functions
Multi-digit decimal add, subtract, multiply and divide demos for the Intel 4004. The ADRT, SBRT, MLRT and DVRT subroutines are taken from code published in "A Microcomputer Solution to Maneuvering Board Problems" by Kenneth Harper Kerns, June 1973 - Naval Postgraduate School Monterey, California.

According to comments in the original code listing, the Decimal Divide subroutine was written by Gary Kildall (of CP/M fame) when he was an assistant professor at the Naval Postgraduate School. He may have written the other decimal arithmetic routines as well.

If you intend to run this code on actual hardware (or in an emulator) you'll probably need to re-work the getchar and printchar functions to suit your particular application.

Assemble the source files with the [Macro Assembler AS](http://john.ccac.rwth-aachen.de:8000/as/).
