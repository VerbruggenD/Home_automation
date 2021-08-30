# Home_automation

This project contains the code for a home automation setup. The system will contain nodes with each a different function.
Node types:
- weather node: a RPI + MCU node to measure weather conditions (temp, hum, vco, press, windsp, winddir, rain)
- hud node: human interface on a rapsberry pi
- connectivity node: the bridge to the outside world (ethernet), will be used as the main node
- controller node: interraction with the existing domotic system to control and measure light status
- power meter node: used to determin efficiency op power usage in combination with the solar system

## Raspberry Pi
The RPI runs the latest version of raspberry pi OS. To install the software on the RPI you have to open the correct node folder and select the RPI-folder. In that folder you have to run the setup.sh, this will automatically start necessary services at boot.

## AVR
To program the microcontroller, open the corresponding folder of the node and run the makefile.