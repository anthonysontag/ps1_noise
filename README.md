Noise-O-Tron
==========

A small, cheap optical theremin that can be assembled with no soldering.

The idea is to laser cut a custom perfboard from acrylic, heavy cardstock or other suitable material.
Components are pushed through the top of this perfboard and the leads are twisted together to form a circuit.

Laser Cutting
=========

![Board Art](https://raw.githubusercontent.com/loansindi/ps1_noise/master/laser_cut_board.png)

In the root of this project there are two PDF files - ten_boards.pdf and thirty_boards.pdf - these are exported from inkscape with vector lines 0.001" in width. I use these files on an Epilog machine - you may need to generate your own for other print driver-based machines.


Assembly
=========

The first challenge to overcome with this device is the fact that DIP packages have very short legs. In the first round of noisemakers I made, we soldered extensions cut from solid-core wire onto the 5 pins used. This sucked.

For the second go, we're using pin headers from Samtec, and trimming off the 3 unused pins. These are a little harder to twist together than the solid-core wire legs, but should be significantly faster to prepare for the event.
