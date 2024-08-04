# Stochastic Gradient Descent (SGD) 

## Overview

This repository contains implementations and analysis of various Stochastic Gradient Descent (SGD) variants as part of a lab session. The objective is to explore different optimization techniques and compare them with the traditional Gradient Descent (GD) method.

## Table of Contents

- [Overview](#overview)
- [Implemented Variants](#implemented-variants)
- [Comparison with Gradient Descent](#comparison-with-gradient-descent)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Implemented Variants

1. **SGD with Constant Stepsizes**: Using a fixed learning rate.
2. **SGD with Shrinking Stepsizes**: Gradually decreasing the learning rate over time.
3. **SGD with Sampling (With/Without Replacement)**: Exploring data sampling strategies.
4. **SGD with Averaging**: Averaging parameters over iterations to reduce noise.
5. **SGD with Momentum**: Incorporating momentum to accelerate convergence and escape local minima.

## Comparison with Gradient Descent

- **Gradient Descent (GD)**: Computes gradients over the entire dataset, providing stable but computationally expensive updates.
- **SGD**: Updates parameters more frequently using individual data points or small batches, efficient for large datasets but introduces noise and requires careful tuning.

## Installation

Clone the repository and install the required dependencies:

```bash
git clone git@github.com:Ignatiusboadi/stochastic_gradient_descent.git
cd sgd-solutions
pip install -r requirements.txt
