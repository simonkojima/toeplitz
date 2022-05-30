# toeplitz

- This package is originally from [toeplitz](https://github.com/trichter/toeplitz) by Trichter.  


Function ccg and cccg was removed from original package since it throws error while building.  
For using the package [blockmatrix](https://github.com/jsosulski/blockmatrix), toeplitzlda.ctg_sl() is only required. Which means, these functions are not required for running [blockmatrix](https://github.com/jsosulski/blockmatrix) and [toeplitzlda](https://github.com/jsosulski/toeplitzlda).

# Requirment
numpy is required.

# Installation
You can install package with following commands. (on ubuntu)

```
sudo apt install gfortran
python setup.py install
```

If it's failed, following commands may help fixing. (only on anaconda)
```
conda install -c conda-forge fortran-compiler
```
