multicolrule - Decorative rules between columns
=================================================

The multicolrule package lets you customize the appearance of
the vertical rule that appears between columns of multicolumn
text. It is primarily intended to work with the multicol
package, hence its name, but it also supports the twocolumn
option and \twocolumn macro provided by the standard classes
(and related classes such as the KOMA-Script equivalents).

Installation
------------

This package is provided as a .dtx file. To install it and
compile the documentation at the same time, simply process the
.dtx file with LaTeX (for example, `pdflatex multicolrule.dtx`).
To extract the package only, process the file with TeX
(`tex multicolrule.dtx`). Note that the documentation uses
the l3doc class to index the code, and so to get the index, you
must issue:

`makeindex -s gind.ist -o multicolrule.ind multicolrule.idx`

and to get the change list, you must issue

`makeindex -s gglo.ist -o multicolrule.gls multicolrule.glo`.

This package requires expl3 and xparse.
