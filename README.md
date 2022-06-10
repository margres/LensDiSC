# LensDiSC

LensDISC is a software package to solve the diffraction integral and obtain the amplification factor for different lensing scenarios. This software takes into account the wave effects that may arise in lensing of rays with a lenght comparable to the Schwarszchild radius of the lens.

# Installation
Download the folder and install it through pip

```console
pip install LensDiSC/
```

# Quickstart

The package can be imported using

```python
import lensdisc
#or
from lensdisc import DiffInt

#run
DiffInt.DInt1D()

DiffInt.DInt2D()
```

or directly 

```python

from lensdisc import  DInt1D,DInt2D

DInt1D()
DInt2D()

```

If a config.ini file is not present in the same folter as the python script it will be automatically created when the package is imported. 
In the config.ini file it is possible to modify the lens parameters and other additional options.
