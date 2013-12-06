Methane and Water Molecule Files
================================

Files necessary to build starting configurations using the
[fftool.py](http://www.github.com/agiliopadua/fftool) utility and
[Packmol](http://www.ime.unicamp.br/~martinez/packmol/), for example:

    fftool.py 1 methane.zmat 360 spce.zmat -r 50

    packmol < pack.in

    fftool.py 1 methane.zmat 360 spce.zmat -r 50 -l -a

The `in.lmp` files have to be modified to introduce the free energy
route and the configuration in the `data.lmp` files should be
equilibrated before proceeding to the free energy calculations.
