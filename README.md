pcb2gcode
=========

A patch to work on Mac OS X Mavericks

Dependent codes
---------------

pcb2gcode has a dependency to the following codes:

boost (>= 2.6.0)
glibmm (2.x >= 2.4)
gdkmm (2.x >= 2.4)
libgerv (from "gerbv" gerber file viewer)

How to compile
--------------

1. patch this with patch -p1
2. exec following commands

- libtoolize
- aclocal
- automake --add-missing
- autoreconf
- ./configure (with an option --prefix directory setting as you prefer)
- make -j

Tested environment
------------------

- Mac OS X 10.9.1 Mavericks
- Xcode 5.0.2 with command line tools
- MacPorts or HomeBrew to install dependent libraries
