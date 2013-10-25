notes-particles
===============

This repository contains Latex files for a set of notes written 
for the "Particle Physics" section of AQA physics A-level.  These 
notes were written by Andrew C. Norman (Teacher of Physics, 
Bishop Heber High School).

License
-------

Full details of the terms under which this work may be used and 
attributed are contained in the file LICENSE.md in this 
directory.

Compiling
---------

The files will only compile properly when the following
LaTeX packages are installed:
- siunitx
- tikz
- graphicx
- hepnames

The document can be compiled by issuing the commands
- `pdflatex notes1-1v3.tex`
- `pdflatex classnotes.tex`

in the base directory (containing classnotes.tex).

The document will need to be compiled a number of times to
update all of the internal references, and to generate the
table of contents data.
