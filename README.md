
# Gradient Descent Optimization Project

## Overview

This project implements gradient descent optimization for linear regression. It includes functionalities for:

- Generating synthetic data.
- Performing gradient descent to minimize the cost function.
- Visualizing the cost function and optimization path in 3D and 2D.
- Displaying the cost function evolution and the resulting best-fit line.

## Features

- **Data Generation**: Generates synthetic data for linear regression.
- **Gradient Descent**: Applies gradient descent to find the optimal parameters (`theta0` and `theta1`).
- **Cost Function Visualization**: Shows the cost function as a 3D surface plot and a contour plot.
- **Optimization Path**: Displays the path of gradient descent optimization in the cost function space.
- **Cost vs Iterations**: Plots the cost function value over iterations to illustrate convergence.
- **Best-Fit Line**: Visualizes the best-fit line after optimization on the data points.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: NumPy, Matplotlib, Plotly, Pandas, Tabulate

## Usage

### Running the Script

To execute the gradient descent algorithm and visualize the results, run the Python script:


python gradient_descent.py

This will generate:

- A 3D surface plot of the cost function with the optimization path.
- A contour plot of the cost function showing the path of gradient descent.
- A plot of the cost function vs iterations to track convergence.
- A scatter plot of the data points with the best-fit line.

### Parameters

- **Learning Rate (`alpha`)**: Controls the step size of each update in gradient descent.
- **Iterations**: Number of iterations for gradient descent.

### Outputs

1. **3D Surface Plot**: Shows the cost function as a surface and highlights the optimization path with markers for the initial and final points.

2. **Contour Plot**: Displays contour lines of the cost function with arrows indicating the path of gradient descent.

3. **Cost vs Iterations Plot**: Plots the cost function value against the number of iterations, showing how the cost decreases over time.

4. **Best-Fit Line Plot**: Illustrates the linear regression line after optimization, overlaid on the scatter plot of the data points.

## Code Description

- **`h(theta0, theta1, x)`**: Hypothesis function for linear regression.
- **`j(theta0, theta1, x, y)`**: Cost function for linear regression.
- **`gradientdes(x, y)`**: Implements gradient descent algorithm, calculates cost, and updates parameters. Also records the optimization path and final parameters.
- **`plot_visualizations`**: Generates and displays various plots to visualize the results of gradient descent.

## Example

Running the script will provide the following outputs:

- **Initial and Final Points**: Indicate where the gradient descent starts and converges.
- **Cost Function Surface**: Visualizes how the cost changes with different parameter values.
- **Optimization Path**: Shows the trajectory of gradient descent on the cost function surface.
- **Best-Fit Line**: Displays the line fitting the generated data points after optimization.

## Notes

- The learning rate (`alpha`) and number of iterations are set to default values but can be adjusted based on specific requirements.
- Ensure you have the necessary Python libraries installed. You can install them using:

  pip install numpy matplotlib plotly pandas tabulate
  
