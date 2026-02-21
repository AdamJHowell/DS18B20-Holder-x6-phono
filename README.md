# DS18B20-Holder-x6
A simple board to hold six DS18B20 temperature sensors

J2 is a jumper to select normal or parasitic-power mode.  Short the middle pin to the one labelled 'n' for normal power mode.  Short the middle pin to the one lebelled 'p' for parasitic-power mode.

R1 is a 4.7 kOhm resistor, though most sensors can tolerate as low as 2.2 kOhm.

If difficulties are experienced, test with shorter wires.

Raspberry Pi code to work with multiple sensors [can be found here](https://github.com/AdamJHowell/RPiDS18B20).

Adruino code can be found [here](https://github.com/AdamJHowell/UnoTFT_DS18B20/).

The 3D printing plans for an Arduino UNO project using this board can be downloaded [here](https://www.thingiverse.com/thing:6745784).

![printed circuit board](https://github.com/AdamJHowell/DS18B20-Holder-x6/blob/master/PCB.png)
![Picture of the front and back of two boards](https://github.com/AdamJHowell/DS18B20-Holder-x6/blob/master/PCB%20front%20and%20back.jpg)
![scematic](https://github.com/AdamJHowell/DS18B20-Holder-x6/blob/master/Scematic.png)
