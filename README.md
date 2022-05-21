# G-Code keeb
A simple keyboard to move your 3D printer toolhead. The layout of both the keyboard and the custom keycaps is heavily inspired on [Pronterface](https://github.com/kliment/Printrun). This keyboard is meant to be used with [Klipper](https://github.com/Klipper3d/klipper), taking advantage of its multi-microcontroller capabilities.

### FAQ
* ***Why?***

Because I'm lazy and I want a better interface to deal with toolhead movement when I'm standing near my 3D printer. Moving to the computer to use a web interface, or using the LCD menu (when available) takes time, with this keyboard I can just press a button.

* ***Where is the USB connector? (Cherry MX 32U4 version)***

I broke it down to a Dupont connector, that gives the user more flexibility to manage the cable.

* ***Why an ATmega32U4-AU version if you are also adding the Raspberry Pi Pico as microcontroller?***

Because I already have some that I bought years before the current components shortage, and since they are already available I might as well use them.

* ***Why have you chosen the CERN Open Hardware Licence?***

Because as much as I love the GPL, it was created for Open Source **Software**. Open Source Hardware is an entirely different beast, with very different concerns and needs to be attended, there's even an [article](https://www.gnu.org/philosophy/free-hardware-designs.en.html) concerning that on the GNU website. This is my first Open Source Hardware project that is in full compliance with the CERN-OHL-S v2 licence, I have others licensed with earlier versions that need to be upgraded *and* modified to be fully compliant, but that's off-topic.

### TODO
* Add instructions on how to flash the ATmega32U4/Raspberry Pi Pico microcontroller with Klipper
* Add instructions on how to configure Klipper to take advantage of this keyboard
* Design a case for all versions

### UPDATES
May 19th, 2022: Initial public release.

May 21st, 2022: Added a tact switch version of the board, using a Raspberry Pi Pico as the microcontroller. Because of that I also reorganized the repository a little bit.
