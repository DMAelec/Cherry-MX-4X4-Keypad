# Cherry MX 4X4 Keypad
A simple 16 key mechanical keypad designed for use with microcontrollers. This keypad is similar to the membrane 
ones used in Arduino projects but instead using Cherry MX switches with backlighting. You can use interface this
with Arduinos or Raspberry Pi, or even use it on a more advanced microcontroller like the teensy or the pro micro 
and load up QMK for a custom macropad.
 
Completely through hole PCB with provisions for 3mm LED backlighting and for NKRO diodes. Designed with Kicad 5.1 and 
files include schematic and drill template for mounting holes.

NOTE: If using NKRO diodes some Arduino sketches won't register keys unless you modify the code or insert the diodes backwards.