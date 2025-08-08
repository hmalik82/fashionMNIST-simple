# CNN on MNIST Dataset (PyTorch)

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset.

## Features

- Loads MNIST dataset using `torchvision.datasets`
- Defines a CNN model with `torch.nn`
- Uses a training loop with manual accuracy calculation
- Visualizes loss and accuracy with `matplotlib`
- Measures performance with `timeit`
- Uses a custom helper module (`helper_functions.py`) for reusable utilities


## Requirements

Install required packages using:

```bash
pip install torch torchvision matplotlib requests
```

or with a requirements file:
```bash
pip install -r requirements.txt
