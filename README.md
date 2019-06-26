# Sugarloop
A waterproof case with inductive charging for RileyLink boards (433 MHz version)

## Case
The waterproof case consists of two parts (top and bottom), is sealed by a silicone seal and held in place by a rubber band. Feel free to print one yourself or have a look at Shapeways if you do not have access to a 3D printer.

### Print settings
Some very decent print result was archieved with the following setup:
- Prusa i3 MK2
- 0.4mm extruder nozzle
- Infill 20%
- High quality PLA, preferable white color to better see the charging led
- Support structure for top of the case with some additional support blockers
- print time for top and bottom about 4 hours

### Seal
The main silicone seal is borrowed from AMP Superseal connector with 6 positions ([Digikey Partnumber A106530-ND](https://www.digikey.com/products/en?keywords=A106530-ND)). Any rubber band with decent tension is good enough to hold to top and bottom of the case in place.

## Hardware

### Inductive charging module
To add reliable inductive charging to the case make sure to use [Adafruits Universal Qi Wireless Receiver Module](https://www.adafruit.com/product/1901). The flex PCB might be cut off (1mm) on the left side in oder to fit the top-case. Connect the charging module to 'ALT PWR' on RileyLink side. Make sure to double check for ground and VCC.

### Battery
The battery compartment can hold up to a 900mAh LiPo battery pack with a standard JST-PH connector (2mm pitch). Make sure there is enough space between the inductive charging module and the LiPo battery due to expansion while charging. Sucessfully tested with a LiPo battery 42mm x 34mm x 6mm.

## Test before use
Please make sure to test your case in a water condition before inserting the electronic components. Small pieces of paper added to the case compartments work fine to detect potential water leaks.
