# mandelbrot-c64
Mandelbrot generator for Commodore 64

Build with cc65:

```
ca65 -t c64 -o mandelbrot.o65 mandelbrot.s65
ld65 -t c64 -o mandelbrot.prg mandelbrot.o65
```
For new cc65:

```
ca65 -t c64 -DNEWCA65=1 -o mandelbrot.o65 mandelbrot.s65
ld65 -C c64-asm.cfg -o mandelbrot.prg mandelbrot.o65
```
