Super simple status bar for DWM (for linux) that will display a flashing message when the battery gets low and will (try to) suspend the system when it gets below the threshold.

do `sudo make install` to install it on your linux box. Then add it to your .xintrc to get it working.

   I however had to use ethe gcc compiler to make it work eg:

```
 sudo make CC=gcc install
```

Gets autoconfigured during make.

The default compiler is clang. The program can be built with any sane C compiler (gcc, tcc, etc). Eg.:

```bash
make CC=gcc
```

