# RH-SB
_broad.c_ file with new evaluation of quadratic Stark effect for certain spectral lines (till now, only Mg II h,k and triplets) in RH code . To use it, just replace the _broad.c_ file in your main directory of RH code.

This is a small change to let your RH code use Mg II Stark widths calculated by semi-classical perturbation theory. Besides,
you can add some other lines like Si IV with a little effort.

Tested on RH1.5D, should also work on 1D verson (rhf1d).

Have fun!

### Some references & Links:
[RH1.5D](https://rh15d.readthedocs.io/en/latest/index.html)
Uitenbroek [2001](https://ui.adsabs.harvard.edu/abs/2001ApJ...557..389U/abstract), Pereira & Uitenbroek [2015](https://ui.adsabs.harvard.edu/abs/2015A%26A...574A...3P/abstract)

Zhu, Y., Kowalski, A. F., Tian, H., et al. 2019, ApJ, 879, 19 [ADS](https://ui.adsabs.harvard.edu/abs/2019ApJ...879...19Z/abstract)

[STARK-B](http://stark-b.obspm.fr/)
Sahal-Bréchot, S., Dimitrijević, M.S., Moreau N., 2018. STARK-B database, online.
http://stark-b.obspm.fr August 29, 2018. Observatory of Paris, LERMA and Astronomical Observatory of Belgrade


