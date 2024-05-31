# The TQFT Package

This is the official home of the development repository for the `tqft`
library for LaTeX.
This package is for drawing cobordism diagrams, as typified in
topological quantum field theory (tqft).

The current published version can be
found [on CTAN](https://ctan.org/pkg/tqft?lang=en) and the
documentation is there as a PDF.

To use the most recent version, download the file `tqft_code.dtx` and
then run `tex tqft_code.dtx` to generate the library file.  The
documentation is in `tqft.tex`.

## Versions

The `TQFT` package has two main versions (both are created by
`tqft_code.dtx` and so both are available in CTAN):

* Version 1: the original version defined the diagrams using
  nodes. To use this version, use `\usepackage{tqft}` in your
  preamble. This version will not get new features, but I'll fix bugs
  (if I can). On CTAN, this was frozen at v2.1 (though it hasn't been
  updated since v1.1).
* Version 2: the most recent version defines the diagrams using
  pics. To use this version, use `\usetikzlibrary{tqft}` in your
  preamble. This is the recommended version and the one that is
  maintained.
  
  

