# diffusion2d

## Description

This code solves the diffusion equation over a two dimensional square domain which is at a certain temperature, and a circular disc at its center which is at a higher temperature. The diffusion equation is solved using the finite-difference method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package

pip install -i https://test.pypi.org/simple/ enoghadd-diffusion2d

## Running this package

You can run the package from command line as follows:

```python
from diffusion2d..diffusion2d import solve

solve(dx=0.1, dy=0.1, D=4.0)
```

## Citing

Information are from:

- https://scipython.com/books/book2/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/
- https://en.wikipedia.org/wiki/Finite_difference_method
