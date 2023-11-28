# ZX-Interface-1-Replacement-ROM
Replacement ROM for the ZX Interface 1

The original ROM for the ZX Interface 1 was a mask programmed device that is now obsolete. This work is based on an idea by Retroleum and others in using an SMD flash device on a PCB in order to remap the pins to suit the original 24 pin devices layout. When using the suggested Samtec pins there is enough room in the Interface 1 to allow the use of Samtec sockets so the ROM can be removed if required. I have not found any other pins that are short enough to allow the use of a socket in the Interface 1. 

This PCB will support SST39SF010, SST39SF020 and SST39SF040 devices and will allow up to a maximum of 32 different ROM images to be used.

The orignal ROM is an 8K device but if address A13 is taken from the ROM and connected to A13 on the expansion BUS then a 16K ROM image by Ian Collier can be used.

This was developed in Kicad 7 and requires an adaptor board to remap the pins when programming.

The adapter board is available under ZX-Interface-1-Replacement-ROM-Programming-Adapter.
