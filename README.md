# Sympy's Symbolic Quantum Mechanics Package

[SymPy](http://www.sympy.org/en/index.html) is a symbolic mathematics library for the [Python](https://www.python.org/)
programming language. SymPy has a subpackage, `sympy.physics.quantum` that implements a general symbolic 
quantum mechanics package for Python, and a number of specific
quantum system on top of that:

* Quantum angular momentum.
* Quantum computing.
* Simple harmonic oscillator.

This repository contains a set of Jupyter Notebooks that
demonstrate the capabilities of `sympy.physics.quantum`.

You can browse static version of these notebooks here on GitHub, or click the `binder` badge below to launch a live Jupyter Notebook server with the notebooks in this repo.

[![Binder](https://beta.mybinder.org/badge.svg)](https://beta.mybinder.org/v2/gh/sympy/quantum_notebooks/master)

## Example

Here is an example of using `sympy.physics.quantum` to create a 3
qubit [Quantum Fourier Transform](https://en.wikipedia.org/wiki/Quantum_Fourier_transform),
decompose the circuit into primitive gates, and then visualize the circuit:

![Quantum Fourier Transform](images/qft_example.png?raw=true)

