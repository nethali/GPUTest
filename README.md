# GPU Availability Test Notebook

## Overview

This Jupyter notebook provides a comprehensive set of tests to check GPU availability and performance in a Python environment. It's designed to help users verify if their system is properly configured for GPU-accelerated computing.

## Features

- Checks CUDA availability
- Displays GPU information (if available)
- Performs matrix multiplication tests on GPU and CPU
- Provides detailed GPU metrics using `py3nvml`
- Executes `nvidia-smi` command for additional GPU details
- Compares NumPy (CPU) performance
- Includes a simple matplotlib plot for visualization testing

## Prerequisites

To run this notebook, you need:

- Jupyter Notebook environment
- Python 3.9 or later
- pip (Python package installer)

## Installation

The notebook will attempt to install the required libraries. However, you can pre-install them using:

```
pip install torch numpy matplotlib py3nvml
```

## Usage

1. Open the `gpu_availability_test.ipynb` file in your Jupyter Notebook environment.
2. Run each cell sequentially to perform the tests.
3. Observe the output to understand your system's GPU capabilities and performance.

## Note

- If a GPU is not available, some sections of the notebook will be skipped.
- The performance results may vary depending on your specific hardware configuration.

## License

Created by Nethali Zoysa on 2024/08/02. This notebook is provided under the MIT License. Feel free to use, modify, and distribute it as needed.
