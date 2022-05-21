# G-Code keeb
A simple keyboard to move your 3D printer toolhead. The layout of both the keyboard and the custom keycaps is heavily inspired on [Pronterface](https://github.com/kliment/Printrun). This keyboard is meant to be used with [Klipper](https://github.com/Klipper3d/klipper), taking advantage of its multi-microcontroller capabilities.

This is the source for the keyboard that uses tactile switches. Unlike the Cherry MX version, it will only support the Raspberry Pi Pico as the microcontroller. The current components shortage made the ATmega32U4 too expensive for anyone who doesn't have some already available at hand, while the Pico (and its microcontroller, the RP2040) is cheap and available due to the Raspberry Pi Foundation's diligence.
