# Batch Gradient Descent Model

## Overview
This project implements a custom Batch Gradient Descent algorithm to perform linear regression on a synthetic dataset representing the relationship between height and weight. The goal is to understand the mechanics of gradient descent and compare its performance with the built-in Linear Regression model from scikit-learn.

## Features
- **Custom Implementation**: A `myregressor` class that encapsulates the gradient descent logic.
- **Data Generation**: Synthetic dataset creation with a known correlation between height and weight.
- **Performance Comparison**: Evaluation of the custom model against scikit-learn's Linear Regression using R² scores.
- **Visualization**: Graphical representation of the prediction lines for both models.

## Getting Started

### Prerequisites
- Python 3.x
- Required libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/batch-gradient-descent.git
   ```
2. Navigate to the project directory:
   ```bash
   cd batch-gradient-descent
   ```
3. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```

### Usage
1. Open the Jupyter Notebook `gradient descent.ipynb`.
2. Run the cells sequentially to create the dataset, train the model, and visualize the results.

## Conclusion
This project provides a hands-on understanding of gradient descent and its application in linear regression. It highlights the importance of each component in building a regression model and offers insights into performance evaluation.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
