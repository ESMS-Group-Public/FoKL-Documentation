# Welcome to FoKL!

FoKL-GPy, or FoKL, is a Python package intended for use in machine learning. The name comes from a unique implementation of Forward variable selection using Karhunen-Loève decomposed Gaussian Processes (GP's) in Python (i.e., FoKL-GPy).

The primary advantages of FoKL are:

- Fast inference on static and dynamic datasets using scalable GP regression
- Significant accuracy retained despite being fast

Some other advantages of FoKL include:
- Export modeled non-linear dynamics as a symbolic equation (i.e., use a GP model in Pyomo)
- Take first and second derivatives of model with respect to any input variable (e.g., gradient)
- User-friendly (e.g., automatic handling of various dataset formats, automatic creation of training set, etc.)
- Easy adjusting of hyperparameters for sweeping through variations in order to find optimal settings
- Ability to save, share, and load models
- Ability to import and evaluate a model without known data (i.e., without training)

# Table of Contents

```{tableofcontents}
```
