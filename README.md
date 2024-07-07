# tiny Entlein - super simple & small Canard VTOL Aircraft
Author: Benjamin Kelm, 31.05.2024

A VTOL demonstrator in a canard configuration.
All up apprx. 400g, with 3S 350mAh LiPo Battery

Based upon the [dRehmFlight](https://github.com/nickrehm/dRehmFlight) controller V1.3 by Nicolas Rehm.

## Electronics
- Teensy 4.1
- MPU6050
- 4 x KISS ESC 18A via OneShot
- 1 x Servo (mini-class, ca. 12 g), preferrably metal-gear
- RC Transmitter & Reciever

## Mechanics
- 4 x brushless motors (here, BetaFPV 1106), apprx. 4500 KV, incl. 3" propellers
- Carbon Tube (here 16mm diameter), Carbon rods for reinforcement & canard hinge

## 3D Print
- Preferrably use Light-Weight PLA (LW-PLA) to save up to 40% weight
- 50% Infill center or nacelle parts
- 20% Infill for general wing structure  

## AVL Model - for flight mechanics analysis
- tE.avl - main AVL file with dimension (! Absolute file paths used here, please change those according to your file structure!)
- tE.mass - Mass file for CG settings
- clarky-il.dat - Aerodynamic Profile file

## CAD Project
[tiny Entlein Onshape Project](https://cad.onshape.com/documents/107a331b13ce1d6b795540c4/w/6723dc1569f4c79b369058ea/e/535ad495e60443d4d2ff6294?renderMode=0&uiState=6659ccdb47e66a2a5d8b56c0)

## Flight Testing
06.07.2024 - Hover Tests: Worked well "out of the box".
07.07.2024 - Maiden Flight: Transition Flight poses yaw issues. Light Pitch Oscillations at higher speeds - no catastrophic failure. CG has to go much further to the front then expected. 


