This firmware has been reverted to FLSUN's official V1.3 release. 

BE SURE TO INCLUDE **MarlinSerial.cpp.o**

The first compilation will fail
then, copy MarlinSerial.cpp.o file to "NanoV3-TFcard\.pio\build\mks_robin_nano_v3_usb_flash_drive_msc\src\src\HAL\STM32"
then ,compile again ,it will succeed

This will happen often, so don't worry if you have to do it again after coming back to it.

Firmware has been modified for:

*Custom Hotend*
Different Esteps
Lower current for motors (XYZ -100 mA)
Lower current for extruder motor (450mA)
I would measure current through potentiometer, changed it on stock firmware through potentiometer.
E3D thermistor is being used for hotend, changed thermistor value from 11 to 5.
