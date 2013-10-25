notes-particles
===============

This repository contains the Latex files required to compile
a set of notes for the "Quantum Physics" section of AQA physics
A-level.  These notes were written by Andrew C. Norman (Teacher
of Physics, Bishop Heber High School).

The files will only compile properly when the following
LaTeX packages are installed:

siunitx
tikz
graphicx
hepnames

The document can be compiled by issuing the command

pdflatex notes1-1v3.tex
pdflatex classnotes.tex

in the base directory (containing classnotes.tex).

The document will need to be compiled a number of times to
update all of the internal references, and to generate the
table of contents data.
