(Vezi [README-ro.md](README-ro.md) pentru o traducere greșită în română.)

# AY-3-8192 interface for Cobra

This is a simple AY-3-8192 interface for the expansion port of the Romanian
microcomputer Cobra.

The interface logic is based on the logic in the [Simple AY interface by
hw.speccy.cz][Simple AY interface], and the output mixing is
based on the Spectrum 128K.

The board has an input for the Cobra's beeper output and mixes it with the
AY-3-8192 output.

NOTE: This revision has not been tested yet.  It includes some simple fixes for
problems in the [previous revision][0da03c1], which is known to work.

[Simple AY interface]: https://hw.speccy.cz/ayinterface.html

[0da03c1]: https://github.com/tsowell/cobra-ay-3-8192/tree/0da03c1

## Images

![Schematic](images/schematic.svg)

![PCB](images/board.png)

![Photo](images/photo.jpg)

(shown with bodges)
