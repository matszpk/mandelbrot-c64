# mandelbrot-c64
Mandelbrot generator for Commodore 64

Build with cc65:

```
ca65 -t c64 -o mandelbrot.o65 mandelbrot.s65
ld65 -t c64 -o mandelbrot.prg mandelbrot.o65
```
