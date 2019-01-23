# Pi-Power

Simple 3 Amp power supply board to power the single board computer over GPIO.  Input should be between 9 and 24 VDC.

Help keep me free to do this sort of thing, if the designs pay for themselves there will be more:
[Donate Here][paypal]

[paypal]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6JRRCSB28828Y&source=url

![Image](https://github.com/Tonymac32/Pi-Power/blob/master/images/board.PNG "board")

Board breaks out SPI and I2C, and provides some 5V 2.54mm headers toward the bottom and some general proto area in the middle.

Simple word of warning:

Do not stick your fingers into this circuit while it's powering something you canre about.  Your fingers have a resistance value, and will change the feedback network regulating the output (R2,4), and/or bridge the compensation circuit (R3,C4) potentially causing a power surge to the board.  Follow typical electrical rules, don't stick your hands into live power supply circuits.
