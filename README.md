# language-mdsp56k assembly highlighting for Atom

* Syntax highlighting for Motorola DSP 56000/DSP56001 assembly language.
* Other DSPs (DSP96000, DSP56100, DSP56300, DSP56800) are not managed although
some common elements may be highlighted.
* Please see Documentation.txt to define your own custom colors.

# Author

David Carrere

Forked from m68k module by François Galea

# Install

To install the package language-m68k:

* In Atom: use app menu to navigate to Packages->Settings View->Install Packages
* Shell: `$ apm install language-mdsp56k`

# TODO

* This version doesn't recognize adresses or constants referenced within instructions.
* Short adressing mode "<" is not highlighted properly.
* Ideally, detect parallel move fields and automatically align them together.


![A screenshot of your package](https://github.com/SplashSD/language-mdsp56k/blob/master/mdsp56k_example.png)
