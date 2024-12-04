# Gradient Descent vs Adam Optimizer

This project compares two popular optimization algorithms—**Gradient Descent** and **Adam Optimizer**—for solving a simple linear regression problem using a randomly generated dataset.

## Overview

In this project, we implemented both **Gradient Descent** and **Adam Optimizer** from scratch to optimize the parameters of a linear regression model. We measured the performance of both algorithms using the Mean Absolute Error (MAE) and \( R^2 \) score.

### Key Components:
- **Dataset Generation**: Randomly generated linear dataset of 100 samples.
- **Optimization Algorithms**: Implemented **Gradient Descent** and **Adam Optimizer** for model optimization.
- **Evaluation Metrics**: Used **MAE** and **\( R^2 \) score** to evaluate the performance of the optimizers.
- **Plotting**: Visualized the cost function across iterations for both optimizers.

## Results

- **Gradient Descent**:
  - **MAE**: 0.5043
  - **\( R^2 \)**: 0.9902
- **Adam Optimizer**:
  - **MAE**: 0.6516
  - **\( R^2 \)**: 0.9842

Despite Adam being a more advanced optimizer, **Gradient Descent outperformed Adam** in this case, demonstrating that for simple problems, traditional methods might work better.


