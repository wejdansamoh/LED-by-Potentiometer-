# LED-by-Potentiometer-

https://www.tinkercad.com/things/1CVtdIIxTb0-ledbypotentiometer


A potentiometer is a three-terminal resistor with a sliding or rotating contact that forms an adjustable voltage divider. If only two terminals are used, one end and the wiper, it acts as a variable resistor or rheostat. Potentiometers are commonly used to control electrical devices such as volume controls on audio equipment.


Components Needed:

Arduino board (Arduino Uno)

Potentiometer

LED

Resistor (220 ohms to 1k ohm, for current limiting the LED)

Breadboard

 wires


 1-Connect the Potentiometer:
 
-Connect one outer terminal of the potentiometer to the 5V pin on the Arduino.

-Connect the other outer terminal of the potentiometer to the GND pin on the Arduino.

-Connect the middle terminal (wiper) of the potentiometer to the analog input pin A0 on the Arduino.


2-Connect the LED:

-Connect the longer leg (anode) of the LED to a resistor.

-Connect the other end of the resistor to digital pin 6 on the Arduino.

-Connect the shorter leg (cathode) of the LED to the GND pin on the Arduino.
