# diffusion2d

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Description

This small example solves the two-dimensional diffusion equation on a square plate using an explicit finite-difference scheme. The implementation is in [`diffusion2d.solve`](diffusion2d/diffusion2d.py). Visualization helpers are provided in [`output.create_plot`](diffusion2d/output.py) and [`output.output_plots`](diffusion2d/output.py).

## Contents

- Main solver: [diffusion2d/diffusion2d.py](diffusion2d/diffusion2d.py) — function [`diffusion2d.solve`](diffusion2d/diffusion2d.py)
- Plot helpers: [diffusion2d/output.py](diffusion2d/output.py) — functions [`output.create_plot`](diffusion2d/output.py), [`output.output_plots`](diffusion2d/output.py)
- License: [LICENSE](LICENSE)
- TOML file: [pyproject.toml](pyproject.toml)
- Ignored files: [.gitignore](.gitignore)

## Requirements

- Python 3.6+
- numpy
- matplotlib

## Installing

Create a virtual environment, then install the required packages (see Requirements)


## Running

To run the example and see the output figures:

```bash
python diffusion2d/diffusion2d.py
```

The script runs the time integration and produces four snapshots. Programmatic use (when the package layout is adjusted for import) can call the solver function [`diffusion2d.solve`](diffusion2d/diffusion2d.py) directly.

## Citing

Example adapted from Chapter 7 of "Learning Scientific Programming with Python":  
https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/

