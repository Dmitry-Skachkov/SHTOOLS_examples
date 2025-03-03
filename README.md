# SHTOOLS examples

[SHTOOLS](https://github.com/SHTOOLS/SHTOOLS/) is the library for spherical harmonic transforms.

## Installation on BRIDGES-2 cluster of PSC

Load intel compiler:

> module load intel-oneapi/2023.2.1

Edit Makefile to change F95 to "ifx"

Compile the code with tests:

> make fortran-tests


## Example

For example of implementation of SHTOOLS library see [ELPOT](https://github.com/Dmitry-Skachkov/ELPOT/tree/main) 
