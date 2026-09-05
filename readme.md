# Numerical Methods for Differential Equations

C++ coursework implementations of numerical methods for ordinary and partial differential equations.

## Projects

| Directory | Topic |
| --- | --- |
| `RungeKutta` | Runge–Kutta methods with configurable coefficient tables |
| `BasicDifferenceScheme` | A basic finite-difference scheme |
| `ODE_2_Order` | A second-order boundary-value problem solved with Fourier and sweep methods |
| `PDE_1` | An implicit method for a partial differential equation |
| `PDE_2` | A two-dimensional Fourier solver and supporting boundary solver |
| `EigenvalueCheck` | Numerical eigenvalue verification with an accompanying report |

## Build and Run

Each directory contains its own `Makefile`. For example:

```bash
cd RungeKutta
make
./a.out
```

Requirements:

- A C++ compiler such as `g++`
- GNU Make
- Gnuplot for regenerating plots from the supplied `.gpi` scripts

Generated values are written to the local `.txt` files. Where plot scripts are present, run them from the same directory so relative paths resolve correctly.

## Notes

This repository is preserved as a numerical-analysis coursework archive. It includes historical outputs and reports alongside the source implementations.
