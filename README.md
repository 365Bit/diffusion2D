# diffusion2D

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description

This code simulates the 2D diffusion equation on a square domain, with the entire domain set to an initial temperature and a circular disc at the center maintained at a higher temperature.
Using the Finite Difference Method, the code solves the diffusion equation, allowing the user to adjust the thermal diffusivity and initial conditions of the system.
The simulation outputs four plots at different time points, vividly illustrating the progression of the diffusion process.

## Installing the package

### Using pip3 to install from PyPI

```bash
pip install --user --index-url https://test.pypi.org/simple/ tischlre_diffusion2d
```

### Required dependencies

```bash
pip install numpy matplotlib
```

## Running this package

```python
from tischlre_diffusion2d.diffusion2d import solve

solve(dx = 0.1, dy = 0.1, D = 4)
```

## Citing


This was forked from https://github.com/Simulation-Software-Engineering/diffusion2D.