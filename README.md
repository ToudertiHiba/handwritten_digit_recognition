# Handwritten Digit Recognition

## Overview
This project implements a handwritten digit recognition system using the MNIST dataset. It consists of a Convolutional Neural Network (CNN) trained on the MNIST dataset to recognize hand-drawn digits.

## Files and Directories
- `.gitignore`: Specifies which files and directories should be ignored by version control.
- `pyproject.toml`: Configuration file for Poetry, a dependency management tool for Python projects.
- `handwritten_digit_recognition.py`: Python script containing the code for the handwritten digit recognition model.
- `handwritten_digit_recognition.ipynb`: Jupyter notebook containing the code for the handwritten digit recognition model.


## Getting Started
1. Install Poetry for dependency management: [Poetry Installation Guide](https://python-poetry.org/docs/#installation).
2. Run `poetry install` to install the project dependencies.
3. Ensure you have the necessary dataset (`spam.csv`) in the project directory.
``


## Dependencies
This project uses Poetry for dependency management. The main libraries used in this project include:

- `keras`: Deep learning library for building neural networks.
- `numpy`: Library for numerical operations in Python.
- `matplotlib`: Library for creating visualizations in Python.
- `scikit-learn`: Library for machine learning in Python.

To install all dependencies, use Poetry as described in the "Getting Started" section.

## Notes
- The model is trained on the MNIST dataset, which consists of handwritten digits from 0 to 9.
- The code supports both training and evaluation of the model. Additionally, you can use the saved model for making predictions on new images.
