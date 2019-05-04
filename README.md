# RH-SB
_broad.c_ file with new evaluation of quadratic Stark effect for certain spectral lines (till now, only Mg II h,k and triplets) in RH code . To use it, just replace the _broad.c_ file in your main directory of RH code.

This is a small change to let your RH code use Mg II Stark widths calculated by semi-classical perturbation theory. Besides,
you can add some other lines like Si IV with a little effort.

Tested on RH1.5D, should also work on 1D verson (rhf1d).

Have fun!

### Some references & Links:
[RH1.5D](https://rh15d.readthedocs.io/en/latest/index.html)
Uitenbroek 2001, Pereira & Uitenbroek 2015
