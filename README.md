# Amiga External Floppy Adapter
![Amiga_external_floppy_adapter (2)](https://user-images.githubusercontent.com/18539931/230749396-5b39c6dc-1d00-4def-bb18-f4b16c55c2c6.jpg)
## Theory of operation
This board allow to connect all type of floppy drives to the Amiga external D-Sub 23 floppy connector;
- Original Amiga "Shugart" drive
- Gotek floppy drive emulator
- IBM-PC floppy drive (720K and 1.44M)

It can operate as DF1, DF2 or DF3, depending on the J4 jumper position.
Two mode of operation are possible;
- Native "Shugart" mode can be selected with J2, J2 and J3 jumper between pin 1 and 2.
- IBM-PC mode can be selected with J2, J2 and J3 jumper between pin 2 and 3.

Onboard logic makes all drive to be seen as 880K standard Amiga floppy drives.

## Schematic
![image](https://user-images.githubusercontent.com/18539931/230749293-f41791b9-1176-4a9e-b3d5-f3554d44c2d8.png)
This drawing has been sketch on OrCAD Capture CIS 10.5.0
## PCB
### Front
![AmigaExternalFloppyAdapter_top](https://user-images.githubusercontent.com/18539931/230749420-7ebd147e-44d0-4e79-91df-1b5ad7245485.JPG)
### Back
![AmigaExternalFloppyAdapter_bottom](https://user-images.githubusercontent.com/18539931/230749426-c163f0d6-a89b-4f83-bb16-cf54656d51e8.JPG)

This PCB has been sketch on WinTypon v8.3
Full compatible Gerber files included
## Bill of material

| Quantity | Designator | Part |
|---|---|---|
| 10 | R1,R2,R3,R4,R5,R6,R8,R9,R10,R11 | 2.2K 1% 0805 |
| 1 | C1 | 10uF 10% 1206 |
| 2 | C2,C3 | 0.1uF 10% 0805 |
| 1 | U1 | 74LVC1G74 SMD |
| 1 | U2 | 74LS38 SMD |
| 3 | J1,J2,J3 | Header 3x1 |
| 1 | J4 | Header 3x2 |
| 1 | CON1 | Header 17x2 |
| 1 | CON2 | D-SUB 23 Male |
| 1 | CON3 | Molex 4 Male |
