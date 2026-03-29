Linux Distribution Timeline | README
------------------------------------

* Copyright (C) 2010-2012 Andreas Lundqvist, Donjan Rodic, Mohammed A. Mustafa
* Copyright (C) 2016 Muhammad Herdiansyah
* Copyright (C) 2016-Onwards Fabio Loli

Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3 or
any later version published by the Free Software Foundation; with no
Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.

Current source: https://github.com/snappyapple632/ConneryFamilyHistory

Original source: https://web.archive.org/web/20220403102136/http://futurist.se/gldt/

### CONTRIBUTING

See CONTRIBUTING.md

### Installation

If you want to build your own version, make sure you have gnuclad
installed.

To install gnuclad, you can download the source at https://launchpad.net/gnuclad

For Arch users, use the AUR: https://aur.archlinux.org/packages/gnuclad/

After you have installed gnuclad, to build just the svg, run:

    gnuclad ldt.csv SVG ldt.conf

You can run the script `build.sh` to build the svg, png, and the tarball
containing the source, ImageMagick is required to convert from svg to png.
