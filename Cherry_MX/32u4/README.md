# G-Code keeb
A simple keyboard to move your 3D printer toolhead. The layout of both the keyboard and the custom keycaps is heavily inspired on [Pronterface](https://github.com/kliment/Printrun). This keyboard is meant to be used with [Klipper](https://github.com/Klipper3d/klipper), taking advantage of its multi-microcontroller capabilities.

This is the source for the keyboard that uses Cherry MX or clones switches *and* an ATmega32U4-AU microcontroller. If you don't have this microcontroller already available at hand, it is better to go with the Raspberry Pi Pico version: it doesn't have any other component other than the switches and the Pico itself to solder (that makes the PCB fabrication cheaper), and the Pico is also cheaper than the 32u4.
