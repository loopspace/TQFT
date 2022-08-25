# The TQFT Package

This is the official home of the development repository for the `tqft`
library for LaTeX.
This package is for drawing cobordism diagrams, as typified in
topological quantum field theory (tqft).

The current published version can be
found [on CTAN](https://ctan.org/pkg/tqft?lang=en) and the
documentation is there as a PDF.

To use the most recent version, download the file `tqft.dtx`.  To
generate the library files, run `tex tqft.dtx`.  To generate the
documentation, run `pdflatex tqft_doc.dtx`.

## Versions

The `TQFT` package has two main versions:

* Version 1: the original version defined the diagrams using
  nodes. To use this version, use `\usepackage{tqft}` in your
  preamble. This version will not get new features, but I'll fix bugs
  (if I can).
* Version 2: the most recent version defines the diagrams using
  pics. To use this version, use `\usetikzlibrary{tqft}` in your
  preamble. This is the recommended version and the one that is
  maintained.
  
  

