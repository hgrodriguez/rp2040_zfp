# rp2040_zfp
RP2040 ZFP Runtime
==================

This code has been created based on https://github.com/JeremyGrosser/pico_bsp from JeremyGrosser.

All credits go to him, as I did just use his code to create this crate to separate the concerns od:
* pico_bsp: the pico board definitions
* zfp_startup: included in pico_bsp

I want to re-use the zfp runtime part for other boards, e.g. ItsyBitsy, Tiny2040 etc. without dragging in the Pico_BSP definitions.


