## Optimization Methods

## Project Description

This repository contains the implementation of classical one–dimensional optimization methods used to find the minimum of a function on a given interval. The project demonstrates how numerical optimization algorithms work and how they reduce the search interval step by step until the optimal solution is found.

The implementations are written in Python and include graphical visualizations to better understand the convergence process of each method.

## Implemented Methods

### 1. Options Method
The options method is one of the simplest optimization techniques. It checks multiple points in the given interval with a fixed step size and finds the point that gives the minimum function value.

### 2. Interval Halving Method
This method repeatedly divides the interval into smaller parts and eliminates regions where the minimum cannot exist. It is more efficient than the enumeration method because it reduces the search space faster.

### 3. Golden Section Method
The golden section search is an efficient optimization algorithm that uses the golden ratio to minimize the number of function evaluations while locating the minimum.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Plotly
- Google Colab

## Project Structure

optimization-methods

01-options-method.ipynb – Options method implementation

02-section-splitting-method.ipynb – Interval halving method implementation

03-golden-section-method.ipynb – Golden section method implementation

## Visualization

The notebooks include graphical representations of the optimization process, showing how the interval decreases and how the algorithm converges to the minimum point.

## Results

The implemented methods successfully find the minimum of the given function and demonstrate the differences in efficiency between the algorithms.

## Author

Victoria Smoyan

