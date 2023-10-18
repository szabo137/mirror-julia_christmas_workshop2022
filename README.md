# Mirror: Julia Christmas Workshop 2022 @ CASUS

This is just the mirror of the day-one material for the Julia christmas Workshop
given at CASUS in Dec2022. 

If you would like to have access to the whole workshop material, send a mail to

Uwe Hernandez Acosta [mailto:u.hernandez@hzdr.de]

## Requirements

To run the notebooks, one needs [jupyter](https://jupyter.org) installed. Zhe only Julia dependence used is
`BenchmarkTools` which you can install using the Julia REPL

```Julia
julia> import Pkg
julia> Pkg.add("BenchmarkTools"
```

To build and run the jupyter notebooks as slideshows, one may use
[`nbconvert`](https://nbconvert.readthedocs.io/en/latest/install.html), and the
script `run_slides.sh` added to the repository:

```bash

$ ./run_slides <name of the notebook>

```
