# Complex Analysis notes

Notes (in italian) for the undergraduate Complex Analysis course (AC310 - Analisi Complessa) at University of Roma Tre, academic year 2016/2017.

The pdf file is available in the Releases.

## Manual build

The notes are compiled via latexmk with the custom class `edoars-notes.cls` found in this repository as a submodule. You will need to have an up-to-date distribution of LaTeX and the Latexmk utility.

First clone the repository and submodules:

``` sh
git clone --recurse-submodules https://github.com/edoars/complex-analysis-notes
```

Then build the notes with `make`:

``` sh
make all
```

The latex document will be compiled into `main.pdf`.