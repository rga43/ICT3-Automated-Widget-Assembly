# ICT3-Automated-Widget-Assembly
FALL 2018

Simon Fraser University Course Project 

MSE 310 Introduction to Electro-Mechanical Sensors and Actuators

This project aims to simulate a typical industrial automation system utilizing the Industrial Control System 3 (ICT3) Unit made by Bytronics. The Industrial Control System 3 combines different functions such as sorting of metal pegs/ plastic rings, widget assembly, inspection and accepting and rejection processes. The ICT3 unit is a small representation of the magnitude of an industrial automation system that can be controlled by a PC and connected to any commonly available PLCs. The entire system is fitted with chain/belt conveyors, 24V direct current actuators, and various industrial sensors for sorting and other system functions. For this project, the overall system is programmed with LabVIEW software by National Instruments.
This project aims to simulate a typical industrial automation system utilizing the Industrial Control System 3 (ICT3) Unit made by Bytronics. The Industrial Control System 3 combines different functions such as sorting of metal pegs/ plastic rings, widget assembly, inspection and accepting and rejection processes. The ICT3 unit is a small representation of the magnitude of an industrial automation system that can be controlled by a PC and connected to any commonly available PLCs. The entire system is fitted with chain/belt conveyors, 24V direct current actuators, and various industrial sensors for sorting and other system functions. For this project, the overall system is programmed with LabVIEW software by National Instruments.

Given randomly placed plastic and metal pegs on the chain conveyor at the back of the ICT3. The sorting station at the top of the chain conveyor uses an infrared sensor to detect the plastic pegs and eject them with a solenoid into the assembly chute. The aluminum metal pegs will continue to proceed with the chain conveyor reaching the bottom of the ICT3 by means of a feeder chute. Once the metal pegs reach the bottom of the feeder chute onto the belt conveyor it will reach the assembly chute. An infrared sensor detects if the assembly chute is currently holding a plastic peg and will accordingly dispense the peg into the hopper with a rotary solenoid. Once a metal peg comes into contact with a plastic peg in the hopper the widget will be assembled. The pegs will continue to move down the belt conveyor towards an inductive, capacitive infrared and fibre optic industrial sensor to determine for the correct assembly of a widgets traversing down the conveyor. If determined to not be correctly assembled a final solenoid at the end of the belt will reject the pegs into a recycle/scrap bin and the full assembles will be allowed to continue into a finished parts tray. Further requirements of the project entail: 
-Develop a robust and fully automated controller for the ICT setup 
-Create an eye-pleasing graphical user interface for the operating system 
-Provide a real-time snapshot of activated/deactivated sensors and actuators 
-The number of processed widgets 
-System efficiency  
-A pause button for system halt  
-A means of system recovery in case of power loss
