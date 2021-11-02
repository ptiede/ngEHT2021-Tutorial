# ngEHT2021-Tutorial


This repository contains the tutorials shown in the ngEHT 2021 software tutorial session. The notebooks are written in either python or julia. 

## Installation

This assumes you have a working installation of python, julia, ipython, and eht-imaging. 

Most systems should have a working version of python installed. For Julia please install the official binaries from [https://julialang.org/downloads/](https://julialang.org/downloads/) and follow the instructions there. To get julia to work with jupyter please then install the IJulia.jl package using the REPL. For example you can do
```julia
using Pkg
Pkg.add("IJulia")
```
which should link to an installed version of jupyter. 


### List of Additional Resources (To add other software packages please file an issue!)



### Imaging and Modeling
  - eht-imaging https://github.com/achael/eht-imaging
  - Themis (soon)
  - DPI https://github.com/HeSunPU/DPI
  - ROSE.jl https://github.com/ptiede/ROSE.jl
  - VIDA.jl https://github.com/ptiede/VIDA.jl


### GRMHD simulations
  - iharm https://github.com/afd-illinois/iharm3d 
  - harmpi https://github.com/atchekho/harmpi 
  - bhac https://bhac.science 
  - Athena++ https://www.athena-astro.app 
  - koral https://github.com/achael/koral_lite 
### Polarized GRRT 
  - ipole (ref) https://github.com/moscibrodzka/ipole
  - ipole-IL (ref) https://github.com/AFD-Illinois/ipole
  - grtrans (ref) https://github.com/jadexter/grtrans
  - raptor (ref ) https://github.com/tbronzwaer/raptor/tree/polarization
### Unpolarized GRRT
  - gray (ref) https://github.com/luxsrc/gray
  - odyssey (ref) https://github.com/hungyipu/Odyssey
  - spectrum
  - igrmonty (ref) https://github.com/AFD-Illinois/igrmonty

