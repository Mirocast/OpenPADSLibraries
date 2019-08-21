# OpenPADSLibraries

Mentor Graphics® PADS logic symbols and PCB packages
====
PADS is a suite of EDA software pruduced by Mentor Graphics®, You can design a schematic by PADS logic and PCB by PADS Layout/PADS Router.
Before that we should design the logic symbols and PCB packages first, that sounds a little trouble
In order to focus on the schematic and PCB design, so I creat this project to make it more faster and convenient.

Take your design from concept to creation with [OpenPADSLibraries](https://github.com/Mirocast/OpenPADSLibraries).


PCB:printed circuit board
SMD:Surface Mounted Device
SMT:Surface Mounted Technology
LS:logic symbol

##Basic Rules
=
>>A certain component may have several logic symbols but only one PCB package.
==
>>A certain PCB package may have many components and logic symbols.
==

Note:
A serial may have several logic symbol and different PCB package, such as ATMEL® ATMEGA328 Serial, 
a certain suffix identify a certain component.

ATmega328-AU     32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP)
ATmega328-AUR		32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP)
ATmega328-MMH		28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328-MMHR		28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328-MU		32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328-MUR		32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328-PU		28P3:28-lead, 0.300” Wide, Plastic Dual Inline Package (PDIP)

ATmega328P-AU  32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP)
ATmega328P-AUR  32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP)
ATmega328P-MMH	28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328P-MMHR	28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328P-MU		32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328P-MUR	32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
ATmega328P-PU		28P3:28-lead, 0.300” Wide, Plastic Dual Inline Package (PDIP)

##About PCB package Name
ATmega328P-MMH	28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)
we call it QFN28-45P400N, that means it a QFN package, 28-pad, Lead Pitch 0.45mm(0.45=45/100), the max of body is 4mm(4=400/100)




	
