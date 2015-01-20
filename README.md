JackScheme is a Scheme interpreter written in Jack for the nand2tetris machine. Compile it with the Jack compiler and run it in the VM emulator.

It's just a REPL for now. Not meant to implement any serious dialect of Scheme. Fairly closely modeled on [this C++ Lisp interpreter](http://howtowriteaprogram.blogspot.com/2010/11/lisp-interpreter-in-90-lines-of-c.html).

Missing stuff:
- Garbage collection
- CONS is currently broken
- Most of the standard library, including any kind of I/O or graphics

Probably quite buggy as well.
