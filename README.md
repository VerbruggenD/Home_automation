# Home_automation

This project contains the code for a home automation setup. The system will contain nodes with each a different function.
Node types:
- weather node: a rpi + mcu node to measure weather conditions (temp, hum, vco, press, windsp, winddir, rain)
- hud node: human interface on a rapsberry pi
- connectivity node: the bridge to the outside world (ethernet), will be used as the main node
- controller node: interraction with the existing domotic system to control and measure light status
- power meter node: used to determin efficiency op power usage in combination with the solar system
