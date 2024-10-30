# Machine-Learning-lab

Here's a simplified version of the README:

---

# Nairobi Office Price Predictor

This project uses linear regression to predict office prices in Nairobi based on office size, using a dataset of office prices and sizes. It optimizes the model using gradient descent and visualizes the results with a line of best fit.

## Project Overview

- **Dataset**: Contains office sizes and prices in `Data/Nairobi Office Price Ex.csv`.
- **Script**: `main.py` reads the data, runs the model, and displays a plot.

## Requirements

You'll need Python 3.x and the following libraries:

```bash
pip install pandas numpy matplotlib
```

## How to Run

1. Clone the repository and navigate to the project folder.
2. Run the script:

   ```bash
   python main.py
   ```

## What It Does

- **Training**: The script trains a linear regression model to find the best-fit line using gradient descent.
- **Output**: It shows the Mean Squared Error (MSE) at each step and the final slope and intercept.
- **Prediction**: It predicts the price for an office size of 100 sq. ft.
- **Plot**: Displays a scatter plot with the regression line showing the relationship between office size and price.
`
