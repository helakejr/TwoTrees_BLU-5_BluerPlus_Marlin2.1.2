Files:

Marlin-2.1.2.TT_BlueR-Plus.zip - Zip file containing the Marlin source.

Robin_nano43.bin - pre-built firmware.

ReadMe.md - This file that you are reading.

This is Marlin 2.1.2 built for the following BLU-5 BlueR-Plus Configuration.
- MKS ROBIN NANO V1.2, CPU: STM32F103VE
- MKS Robin TFT43 V1.0
- 3D touch
- Drivers: 5xTMC2209
- Stepper Motors: X,Y,Z/Z2,E0
  Usongshine 42SHDC3045Z-16BD
- Stepper Motors: X,Y act like 0.9° motors.

Changes:
- Different Drivers: configure steps, 1.8 degree motor verion included in configuration.h
  as a comment.
- I started with the github.com Marlin 2.1.2 Configurations for Bluer Plus
- PLEASE check your nozzle to probe Z-offset. Default Was -2.8 however mine was -2.0.
