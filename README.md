# The Snark Barker Mini - a miniaturized SB 1.0 Clone

The Snark Barker Mini is a function compatible clone of the original [Snark Barker](https://github.com/schlae/snark-barker), made by schlae. It implements all the features, including the digital
sound playback and recording, Ad Lib compatible synthesis, the joystick/MIDI
port, and the CMS chips (which are actually Philips SAA1099 synthesizer
devices).

## The Firmware
There are two ways to get a programmed 80C51 chip for the Snark Barker. One
is to purchase a SB 2.0 DSP chip from China and put it in a 44-PLCC to
40-DIP adapter. This works fine and provides the largest feature set.

Another option is to buy a blank Atmel 89S51 (as listed in the BOM) and
program it with [this HEX file](firmware/sb.hex).


## Testing and Diagnostics
The card can be tested using schlae's [SBDIAG](utility/SBDIAG.EXE)

