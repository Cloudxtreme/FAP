FAP aka FreakinAwesomePromt
===========================

This thing changes your bash prompt into something more usefull.
It defaults to a nice colored prompt that includes some basic git info and a timestamp.

Installation

I assume you clone everyting into ~/git .

    git clone https://github.com/dmeulen/FAP.git
    echo ". ~/git/FAP/faprc" >> ~/.bashrc

Log out and log in. There you have it, start fapping...

Usage:

    fap [off|on|gitoff|giton|nocolor|dos|xterm]

    off|gitoff
      Switches off git mode. Git mode can be slow when on a slow network.

    on|giton
      Yes, it switches git mode on!

    nocolor
      Wrong name as it switches off all other stuff including colors.

    dos
      Stupid and simple prompt.

    xterm
      Git mode on and sets xterm title.
