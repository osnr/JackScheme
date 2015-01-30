JackScheme is a Scheme interpreter written in Jack for the nand2tetris machine. Compile it with the Jack compiler and run it in the VM emulator.

It's just a REPL for now. Not meant to implement any serious dialect of Scheme. Fairly closely modeled on [this C++ Lisp interpreter](http://howtowriteaprogram.blogspot.com/2010/11/lisp-interpreter-in-90-lines-of-c.html).

Missing stuff:
- Garbage collection
- Most of the standard library, including any kind of I/O or graphics, or even comparisons (only implemented functions are car, cdr, and cons)
- Hacky error reporting (so if you use an undefined symbol or something like that in certain places, it'll just crash)
- Variables/state

Probably quite buggy as well.
