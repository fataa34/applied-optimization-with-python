# Applied Optimization with Python

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![NumPy](https://img.shields.io/badge/library-NumPy-lightgrey.svg)](https://numpy.org/)

A comprehensive collection of numerical optimization algorithms implemented in **Python**, based on the methodologies and mathematical foundations presented in **"Applied Optimization with MATLAB Programming" by P. Venkataraman**.

## 📌 Project Overview

This repository serves as a bridge between the classic engineering optimization techniques typically implemented in MATLAB and the modern Python data science ecosystem. The goal is to provide clean, efficient, and "from-scratch" implementations of optimization solvers using **NumPy**, **SciPy**, and **SymPy**.

## 🚀 Algorithms Implemented

The implementations are organized according to the optimization categories discussed in the reference text:

### 1. One-Dimensional Search Methods
* Golden Section Search
* Newton-Raphson Method
* Polynomial Interpolation Methods

### 2. Unconstrained Multivariable Optimization
* **Gradient-Based:** Steepest Descent, Conjugate Gradient (Fletcher-Reeves).
* **Newton's Methods:** Classic Newton, Quasi-Newton (DFP, BFGS).
* **Direct Search:** Nelder-Mead Simplex, Random Walk.

### 3. Constrained Optimization
* Penalty and Barrier Function Methods.
* Sequential Linear Programming (SLP).
* Sequential Quadratic Programming (SQP).

## 🛠️ Requirements

To run these scripts, you will need:
* Python 3.x
* NumPy
* SciPy (for comparison/validation)
* Matplotlib (for visualization of convergence)
* SymPy (for automated gradient/Hessian calculation)

```bash
pip install numpy scipy matplotlib sympy

```

## 📂 Directory Structure

```text
├── src/
│   ├── unconstrained/
│   │   ├── steepest_descent.py
│   │   └── bfgs.py
│   ├── constrained/
│   │   └── sqp_solver.py
├── notebooks/          # Step-by-step visualizations
├── tests/              # Validation against benchmark functions
└── README.md

```

## 📖 Reference

* **Book Title:** Applied Optimization with MATLAB Programming
* **Author:** P. Venkataraman
* **Publisher:** Wiley

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

---

*Developed as part of academic research and practical exploration of numerical methods.*

```

---

### Key Features of this Draft:
* **Visual Badges:** Makes the repo look professional and maintained.
* **Categorization:** Grouping by "Unconstrained", "Constrained", and "Heuristic" makes it easy for others to navigate.
* **Mathematical Context:** Mentions **Hessian** and **Gradient** calculations (using SymPy), which shows you understand the underlying calculus.
* **Benchmark Mention:** Mentions a `tests/` folder for validation, which is a hallmark of high-quality code.

Would you like me to help you write a specific Python script for one of the solvers (like **BFGS** or **SQP**) to include in this repo?

```
