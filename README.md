# PlexHD X79 Turbo V1.03

This project created for working macOS Mojave (10.14.6)  Clover Configuration. Worked with this board and Xeon 5-2640 V.1 CPU with Sapphire RX570 graphics. Builds will be updated at future.
EFI for Mojave, Catalina, BigSur I added : OpenCore.

## Guide

SMBIOS iMacPro1,1. serial number is from the lamp, put your own.

* It will also work on the stock Bios, but I rewired to unlock the MSR 0xE2 registers.
* Download BIOS MOD@MierivaL [here](https://drive.google.com/file/d/1r2-3JxFvDSyjUN4ojybZdre0qOoWpVct/view) and video guide on bios firmware [here](https://www.youtube.com/watch?v=B0JyWfsyLKU&t=552s)
* SSDT generated for e5-2640!!!
* for some other CPUs in the archive SSDT-1.zip
* DSDT inside the EFI directory processor only E5-2640!!!
* separate DSDT.aml file for any processor

X86PlatformPlagin the CPU power is turned on and the speedstep is working correctly.

AGPMInjector.kext generated for Sapphire RX570.

USB the external ones are wound up, the 3.0 ones are running at full speed and on power.

Huge thanks: [@Ubikfr](https://github.com/Ubikfr)

Website Overclocker and @Mierival 

# Added EFI OpenCore 0.6.8, works with all systems from Mojave to BigSur
* DSDT inside the EFI directory processor only E5-2640!!!
* separate DSDT.aml file for any processor
