# pirix
Emulation of SGI's IRIX desktop environment on Raspberry Pi.

[http://github.com/rhaleblian/pirix/blob/master/screenshot0.png]

## Installation

    sudo apt install mwm libmotif-dev motif-clients freeglut3-dev
   
Examine the 'install' Make rule and confirm it won't whack any file you want to keep.

    cat Makefile

If it's safe, invoke the install rule.

If you want the atlantis demo,

    cd atlantis
    make
    ./atlantis

## Notes
SGI's Indigo Magic Desktop and Interactive Desktop were derivations from the Motif Window Manager;
this tweak bases itself on mwm.

A lot of things aren't here, including the file manager and the web browser.

## TODO
* add icon images for terminal, emacs, etc
