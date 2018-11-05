# nesasm

A NES assembler written in C.

The source code was based off bunnyboy's modifications of the original NESASM,
available [here](http://www.nespowerpak.com/nesasm/NESASM3.zip).

Main differences from the original:
  * PC-Engine support was removed
  * Uses CMake as build tool

## Install

You will need [CMake](https://cmake.org/) for building. After installing and
cloning the repository do the following:

```
mkdir build
cd build
cmake ..
make
sudo make install
```

## License

This program is freeware. You are free to distribute, use and modifiy it as you
wish.

Original 6502 version by:
* J. H. Van Ornum

NES version by:
* Charles Doty

Further modifications by:
* bunnyboy, from [RetroUSB](https://www.retrousb.com/)
