
2010-05-08
----------

avrpocsag_attiny2313.patch contains some minor modifications 
required to run the N2RVQ's AVR POCSAG code (at90s2313) on attiny2313.

The patch is applied against "avr pocsag rev 1_1.asm" in the current
working directory as follows:

$ patch -p0 < avrpocsag_attiny2313.patch

You need the N2RVQ's AVR POCSAG source code to apply this patch.
Please Google for more information on using patch utility under your OS.

The md5 sum of the patch file is:

$ md5sum avrpocsag_attiny2313.patch
69f7e8b7ebab65f31ea68d14c24a79a9  avrpocsag_attiny2313.patch

73,

Lasse 
OH3HZB
