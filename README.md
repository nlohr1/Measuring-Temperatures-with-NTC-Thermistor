# Measuring Temperatures with a simple NTC-Thermistor
Measuring Temperatures with an ATmega328 microcontroller and a simple 3950-NTC-Thermistor with 100kΩ Resistance.
Enclosed are the Eagle-schematics + layout for a smaller layout (⇒ smaller case-outline).  
But an "Arduino-Mini-Pro" board also may be used, connected through wires to the OLED-Display.

For better and more accurate contacts I often use gold-plated *lower and finer* 0.1"-Connectors (about 3mm height). They are smarter and therefore more resistant against loose contacts as the normally used thicker 0.1"-connectors (~11mm height), which are coarser to connect and therefore easier to bend as former ⇒ Loose + bad contacts are the greatest source for electronic faults!

The board is programmed through an external Arduino-Serial-Programmer (per FTDI-Serial-Connector as used by the Arduino-Pro-Mini board).
The USB-Connector on this layout used here only serves to connect an external 5V-Supply. It has no Voltage-Stabilizer nor Serial-translation to the µController as other boards have (like the Arduino-Nano).
![NTC-Control-Board_sch_ _pcb](https://github.com/nlohr1/Measuring-Temperatures-with-NTC-Thermistor/assets/49346586/b0db3ac9-9767-47c0-81dd-5c1f5ca14bdb)
