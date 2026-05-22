# Linear Algebra with Applications in Machine Learning

<a href="https://link.springer.com/book/9789819551668"><img src="/book-cover.png" alt="The book cover of 'Linear Algebra with Applications in Machine Learning' by Md. Jalil Piran" align="left" height="200px" /></a>

This repository contains the Jupyter notebooks accompanying the book [Linear Algebra with Applications in Machine Learning: From Intuitive Understanding to Python Coding](https://link.springer.com/book/9789819551668), written by [Md. Jalil Piran](https://github.com/jalil-piran) and scheduled for publication by Springer Singapore.

There is one notebook for each chapter. The notebooks combine short mathematical explanations, numerical examples, visualizations, and Python code so you can follow the book from the foundations of vectors and matrices through optimization, decompositions, PCA, and other machine learning applications.

Springer lists the hardcover edition as due on 2 July 2026. Until then, this repository can be used as the companion source code for reading, teaching, and experimenting with the book material.

## Prerequisites

Chapter after chapter, you will explore linear algebra concepts with executable Python examples. Along the way, you will need the following software installed.

* Python 3.10+
* Jupyter
    * [JupyterLab](https://jupyter.org/)
    * [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/)
* Scientific Python libraries
    * [NumPy](https://numpy.org/)
    * [SciPy](https://scipy.org/)
    * [SymPy](https://www.sympy.org/)
    * [Matplotlib](https://matplotlib.org/)
    * [scikit-learn](https://scikit-learn.org/)
    * [TensorLy](https://tensorly.org/)

## Running the Notebooks

The examples are provided as standalone Jupyter notebooks. You can create a virtual environment, install the common dependencies, and launch Jupyter from the repository root.

Task | Command
---- | -------
Create a virtual environment | `python -m venv .venv`
Activate it on macOS/Linux | `source .venv/bin/activate`
Activate it on Windows | `.venv\Scripts\activate`
Install notebook dependencies | `python -m pip install jupyterlab numpy scipy sympy matplotlib scikit-learn tensorly`
Start JupyterLab | `jupyter lab`
Start classic Notebook | `jupyter notebook`

## Guides, Tools and Tips

* Work through the notebooks in chapter order when following the book for the first time.
* Re-run all cells after changing a notebook so figures, symbolic outputs, and numerical results stay consistent.
* Use JupyterLab or VS Code for the best experience with inline plots and interactive exploration.
* Chapter 4 uses TensorLy for tensor decompositions; install `tensorly` before running it.
* Chapters 1 and 13 include examples connected to machine learning workflows such as PCA and low-rank approximation.

## Source Code by Chapter

| Chapter | Notebook | Main topics |
|---------|----------|-------------|
| 1. Introduction to Linear Algebra for Machine Learning | [Chapter_01_Introduction.ipynb](Chapter_01_Introduction.ipynb) | Linear and non-linear functions, data representation, PCA, sparse matrices |
| 2. Vectors | [Chapter_02_Vectors.ipynb](Chapter_02_Vectors.ipynb) | Vector geometry, components, magnitude, direction, 2D and 3D visualization |
| 3. Matrices | [Chapter_03_Matrices.ipynb](Chapter_03_Matrices.ipynb) | Matrix definitions, dimensions, special shapes, matrix operations |
| 4. Tensors | [Chapter_04_Tensors.ipynb](Chapter_04_Tensors.ipynb) | Tensor basics, indexing, Einstein summation, tensor decompositions |
| 5. Linear Systems | [Chapter_05_Linear_Systems.ipynb](Chapter_05_Linear_Systems.ipynb) | Systems of equations, unique/no/infinite solutions, visual solution cases |
| 6. Linear Transformations | [Chapter_06_Linear_Transformations.ipynb](Chapter_06_Linear_Transformations.ipynb) | Transformations, kernel and image, injectivity, surjectivity, inverses |
| 7. Determinants | [Chapter_07_Determinants.ipynb](Chapter_07_Determinants.ipynb) | 2D area, 3D volume, singular matrices, determinant geometry |
| 8. Eigenvalues and Eigenvectors | [Chapter_08_Eigenvalues.ipynb](Chapter_08_Eigenvalues.ipynb) | Eigenvectors, eigenvalues, characteristic ideas, geometric intuition |
| 9. Vector Spaces and Subspaces | [Chapter_09_Vector_Spaces.ipynb](Chapter_09_Vector_Spaces.ipynb) | Vector space axioms, subspaces, planes, null spaces |
| 10. Orthogonality | [Chapter_10_Orthogonality.ipynb](Chapter_10_Orthogonality.ipynb) | Norms, distance, dot products, projections, Cauchy-Schwarz inequality |
| 11. Matrix Decompositions: Factorization and SVD | [Chapter_11_Decompositions.ipynb](Chapter_11_Decompositions.ipynb) | Matrix norms, QR, LU, spectral decomposition, singular value decomposition |
| 12. Optimization and Gradients | [Chapter_12_Optimization.ipynb](Chapter_12_Optimization.ipynb) | Gradient descent, learning rates, 1D and 2D optimization examples |
| 13. Advanced Topics in Linear Algebra for ML | [Chapter_13_Advanced_Topics.ipynb](Chapter_13_Advanced_Topics.ipynb) | Moore-Penrose pseudoinverse, low-rank approximation, PCA, spectral methods |

## Book Page

You can find bibliographic information and publication details on the official Springer page for [Linear Algebra with Applications in Machine Learning](https://link.springer.com/book/9789819551668).

## Feedback

Questions, corrections, and suggestions are welcome. Please open an issue in this repository so the notebooks can keep improving alongside the book.
