# OpenPADSLibraries

PADS logic symbols and PCB packages
====
PADS® is a suite of EDA software pruduced by Mentor Graphics®, you can design a schematic by PADS® logic and PCB by PADS® Layout/Router. Before that we should design the component logic symbols and PCB packages first, that sounds a little trouble.<br>  
So, in order to focus on the schematic and PCB design, I creat this project to make it more faster and convenient.<br>  

Some abbrs in this project:<br>
PCB:printed circuit board <br>
PCBA:PCB Assembly<br>
SMT:Surface Mounted Technology <br>
SMD:Surface Mounted Devices <br>
THT:Through Hole Technology <br>
THD:Through Hole Devices <br>

NPTH:Non PLATING Through Hole <br>
PTH: PLATING Through Hole <br>
DIP:Dual Inline-pin Package <br>
LS:logic symbol, some of time we also call it component symbol or device symbol <br>
IC:Integrated Chip <br>
DS:Data Sheet <br>

##Basic Rules
==
>>A certain component may have several logic symbols but only one PCB package.<br>  
>>A certain PCB package may have many components and logic symbols.<br>
>>For some common components, a logic symbol may have many PCB packages, such as resistance, capacitance, inductance and so on.<br>

<br>
![image](https://github.com/Mirocast/OpenPADSLibraries/raw/master/M1_SIM800L/SIM800L-LogicSymbol.jpg)<br>
![image](https://github.com/Mirocast/OpenPADSLibraries/raw/master/M1_SIM800L/SIM800L-PCBPackage.png)<br>
Note:<br>  
A serial may have several logic symbol and different PCB package, such as ATMEL® ATMEGA328 Serial, a certain suffix identify a certain component.<br> 
<br> 
ATmega328-AU	        32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP) <br>  
ATmega328-AUR		32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP) <br>  
ATmega328-MMH		28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF) <br>  
ATmega328-MMHR		28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF) <br>  
ATmega328-MU		32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF) <br>  
ATmega328-MUR		32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF) <br>  
ATmega328-PU		28P3:28-lead, 0.300” Wide, Plastic Dual Inline Package (PDIP)<br>  
<br>  
ATmega328P-AU    32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP)<br>  
ATmega328P-AUR    32A: 32-lead, Thin (1.0mm) Plastic Quad Flat Package (TQFP)<br>  
ATmega328P-MMH    28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)<br>  
ATmega328P-MMHR    28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)<br>  
ATmega328P-MU    32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)<br>  
ATmega328P-MUR    32M1-A:32-pad, 5 x 5 x 1.0 body, Lead Pitch 0.50mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)<br>  
ATmega328P-PU    28P3:28-lead, 0.300” Wide, Plastic Dual Inline Package (PDIP)<br>  
<br>

##About PCB package Name<br>  
ATmega328P-MMH	28M1:28-pad, 4 x 4 x 1.0 body, Lead Pitch 0.45mm Quad Flat No-Lead/Micro Lead Frame Package (QFN/MLF)<br>  
we call it QFN28-45P400N in OpenPADSLibraries, that means it a QFN package, 28-pad, Lead Pitch 0.45mm(0.45=45/100), the max length of body is 4mm(4=400/100), Narrow body<br>

If a component have no certain package name in DS, we often name it SMD or DIP simply. If I made some mistakes, please send email to me.<br>

##Example
==
M1_A9/A9G<br>
GSM/GPRS Module<br>
SMD56-120P1920N: 28-pad, 2-gnd-pad, 19.2mm x 18.8mm x 2.7mm body, Lead Pitch 1.2mm Surface Mounted Device Package<br>

IC1_ICM-20602<br>
6-Axis(3-axis gyroscope, 3-axis accelerometer) motion tracker IC<br>
LGA16-50P300N： 16-pad,  3mm x 3mm x 0.75mm body, Lead Pitch 0.5mm LGA Package<br>

IC2_ICM-20948<br>
9-Axis(3-axis gyroscope, 3-axis accelerometer, 3-axis compass)  and a Digital Motion Processor™ (DMP™).<br>
QFN25-40P300N： 25-pad, 1-thermal-pad, 3mm x 3mm x 0.9mm body, Lead Pitch 0.4mm QFN Package.<br>

D1_1N4148<br>
  A type of diode.
DO-35, SMA, SOD-123, SMA(DO-214AC), SMB(DO-214AA)

Take your design from conception to creation with [`OpenPADSLibraries`](https://github.com/Mirocast/OpenPADSLibraries 
"www.mirocast.com").<br>
<br>
==
`Enjoy the fun of making!`<br>


