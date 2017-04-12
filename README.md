# Fork pulled by Tachyon to preserve the project. Commits accepted.
# Original file and comments follow
#  --------------------------------------------------------

# TF530 (Archived)

## I am no longer working on this. Do not ask for support.

This repository contains all the files needed to produce a copy of my accelerator board.

The CPLD Required is a XC9572XL-10VQ64

Everything in this repository is released under the GNU GPLv2. You may create or base commercial PCBs from the work in this repository but you must make the sources for all derivative work available. 

## Firmware / Requirements

  * Xilinx ISE, 14.7 (the final version - other versions may work but this is the one I support)
  * JTAG Adaptor

[For more information visit my channel](https://www.youtube.com/c/TerribleFire)

##License

This project and all the files contained are released under the GNU GPLv2. If you build a modified version of the board you must supply the end user with all the sources (this can be a web link).

##The TerribleFire 530 board (Revision 2)

This board is now in Beta. It may not work in all circumstances but it has been verified to boot AmigaOS 1.3, 2.05 and 3.1 and run various games and desktop apps at 25Mhz. Operation is not guarunteed to be crash free but will work in most "happy path" situations.

I have only verified the HD interface with Compact Flash cards.
I have verified this board boots on Amiga 500 Rev 5, 6a, 8.1a

I accept no responsibiltiy for any damage to any equipment that results from the use of this board. IT IS ENTIRELY AT YOUR OWN RISK!

## Installation

Installation is exactly the same as the Kipper2k A508. Refer to http://www.kipper2k.com/a500fastmem.html

You need to connect the OVR and INT2 signals to the A500 header port. 

## What does the board look like

![Image of Top of PCB](gerbers/tf530_rev2_top.jpg)

![Image of Bottom of PCB](gerbers/tf530_rev2_bottom.jpg)

## The BOM 

BOM converted to spreadsheet and now stored in DOCS (Tachyon)
