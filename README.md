# TYMA-2020

A repository containing several programs, methods and utilities for performing sequence comparison.

## Use

1. First clone or download this repository from: https://github.com/estebanpw/pydotplot

2. If on linux, run "make all" to compile. If on windows, use "gcc src/generate_dotplot.c src/common.c -o bin/generate_dotplot"

3. Make sure you have python 3 installed. You can download it from here: https://www.python.org/downloads/

4. Add the following libraries to your python installation:
 - pip install numpy
 - pip install matplotlib
 
## Running dotplots

Run the dotplot generator as "./bin/generate_dotplot fastaX fastaY outdotplot"

This will generate a dotplot file which you can plot using "python ./bin/dotplot.py outdotplot"

And a .png will be created on the folder

## Creating word dictionaries

Run bin/dictionary fastas/hemoglobine.fasta output/dictionary

A dictionary will be created on folder output/dictionary
