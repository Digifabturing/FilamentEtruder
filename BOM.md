### BOM
- n.1 E3D Titan Extruder (https://e3d-online.com/titan-extruder)
- n.1 rs232 - ttl converter (http://users.ntua.gr/dpiperid/MyWebPage/Contructions/converters/rs232tottlEN.htm)
- n.1 24V Power Supply (https://e3d-online.com/24v-power-supply-16-5a-400w)
- n.1 Rumba 3D Printing Electronic Board (http://reprap.org/wiki/RUMBA)
- n.1 piece of 100x100 cm birch plywood
- n.1 Marlin Firmware for 3D printer (https://github.com/MarlinFirmware/Marlin)

### Serial port connection
the Rumba board is connected to the COMAU robot NJ60 through serial communication, for that we have used the rs232 to ttl converter. You will connect the RX from the converter to the Rumba TX(PIN1) and the TX from the converter to the Rumba RX(PIN0), and the GND from the converter to the Rumba GND.

### Extruder and Board setup
In order to assemble the extruder and setup the Marlin firmware follow the E3D guide(https://wiki.e3d-online.com/Titan_Assembly)
