# diffusion2d

## Description

Solves the two-dimensional diffusion equation on a square plate using an explicit finite-difference scheme. The implementation is in [`diffusion2d.solve`](diffusion2d/diffusion2d.py). Visualization helpers are provided in [`output.create_plot`](diffusion2d/output.py) and [`output.output_plots`](diffusion2d/output.py).



## Installing the package

Create a virtual environment, then install the required packages:
- Numpy
- Matplotlib
- Python

Afterwards the actual package can be downloaded via
```bash
pip install --index-url https://test.pypi.org/simple/ reinvt-diffusion2d

```

## Running this package

To run the example and see the output figures:

```
import reinvt_diffusion2d
```
or
```
from reinvt_diffusion2d import solve, output_plots, create_plots
```
The simulation can then be run by:

```
reinvt_diffusion2d.solve()
```
or if you have you have imported solve directly from reinvt_diffusion2d:
```
solve()
```

Because standard values are implemented into reinvt_diffusion2d.solve(), it can easily be tested. However if you want to change the input parameters, that is also possible!
The script produces several PNG snapshots by default. The solver function can be imported directly for programmatic use once the package is installed or the import paths are adjusted.

## Citing

Example adapted from Chapter 7 of "Learning Scientific Programming with Python":  
https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/

