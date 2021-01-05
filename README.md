# IEC64W - IEEE-488 Interface for Commodore C64 & C128

![](https://github.com/DL2DW/IEC64/blob/main/Images/IEC64W_Interface.jpg)



## Introduction

This is the replica of the IEC64 card from the 80's. It provides a GPIB (IEEE-488) connection and plugs into the expansion port of the Commodore C64 or C128.

Who the original developer of the card was, I could not find out. It was sold by "WAW Elektronik", "Jann Datentechnik" and "REX Datentechnik" in different versions, but the technical base and the kernal was always the same. With the Kernal only the switch-on message had been adapted according to the company.

This is the version that was sold by "WAW Elektronik" at that time.



# Technical

The card is based on Motorola's MC6821P Peripheral Interface Adapter. Furthermore the corresponding kernal file is directly integrated as EPROM on the card. 

So the card can be simply plugged into the computer and started immediately. The Kernal, as well as the whole card can be deactivated by DIP switch. The former is interesting if you want to run the Kernal internally in the computer.

The card can be set up in such a way that mixed operation of IEC, for example a 1541, and IEEE-488 is possible.



# BOM

The parts list is quite clear. You can get the MC6821P quite well via eBay or UTSource. Otherwise, I have named the brands as representatives. Comparison types of other manufacturers can also be taken.

| Quantity | Designator      | Manufacturer 1     | Manufacturer  Part Number 1 | Description                                                  |
| -------- | --------------- | ------------------ | --------------------------- | ------------------------------------------------------------ |
| 4        | C1,  C2, C3, C4 | Dersonic           | CC1H104ZA1PD3F5O3000        | Ceramic  Disc Capacitors 100nF -20%~+80% 50V Through Hole,P=2.54mm RoHS |
| 1        | J2              | L-Com              | CIB24SRA                    | L-COM  - CIB24SRA - CONNECTOR GPIB R/A FEMALE                |
| 2        | R1,  R2         | Yageo              | CFR-25JB-52-1K              | RES  1K OHM 1/4W 5% AXIAL                                    |
| 1        | RN2             | Vishay  Dale       | CSC06A0110K0GPA             | RES  ARRAY 5 RES 10K OHM 6SIP                                |
| 1        | RN1             | Vishay  Dale       | CSC05A0110K0GPA             | RES  ARRAY 4 RES 10K OHM 5SIP                                |
| 1        | (SW1  & SW2)    | Wurth  Electronics | 418117270906                | DIP  SWITCH 2.54MM PITCH 6POL 24V                            |
| 1        | U4              | Spansion           | AM27C128-150DC              | EPROM  UV 128K-Bit 16K x 8 150ns 28-Pin CDIP                 |
| 1        | U2              | Texas  Instruments | SN74LS11N                   | IC  GATE AND 3CH 3-INP 14DIP                                 |
| 1        | U1              | Texas  Instruments | SN74LS00N                   | IC,  74LS, 74LS00, DIP14, 5.25V                              |
| 1        | U3              | Motorola           | MC6821P                     | PERIPHERAL  INTERFACE ADAPTER (PIA)                          |



# PCB

The PCB can either be ordered directly from [PCBWay](https://www.pcbway.com/project/shareproject/IEC64W___IEEE_488_for_Commodore_C64___C128.html), or you can create it yourself from the Gerber files available here.

[![PCBWay](https://www.pcbway.com/project/img/images/frompcbway.png)](https://www.pcbway.com/project/shareproject/IEC64W___IEEE_488_for_Commodore_C64___C128.html)



If you liked my project, I would be very happy about a small coffee donation.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R62T6RN)





# License

The contents of this repository, with the exception of the Docs and Software directories, are released under the following license:

- the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (CC BY-NC-SA 4.0) full text of this license is included in the [LICENSE.CC-NC-BY-SA-4.0](https://github.com/DL2DW/IEC64/blob/main/LICENSE.CC-NC-BY-SA) file and a copy can also be found at https://creativecommons.org/licenses/by-nc-sa/4.0/
