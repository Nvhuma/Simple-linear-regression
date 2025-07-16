# Simple Linear Regression

This project demonstrates a simple linear regression model using Python and scikit-learn. The model predicts salaries based on years of experience.

## Files

- `simple_linear_regression.py`: Main script for training, predicting, and visualizing the regression model.
- `Salary_Data.csv`: Dataset containing years of experience and corresponding salaries.

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

Install dependencies using:
```
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Place `Salary_Data.csv` in the project directory.
2. Run the script:
   ```
   python simple_linear_regression.py
   ```
3. The script will display visualizations for both the training and test sets.

## How it works

- Loads the dataset.
- Splits data into training and test sets.
- Trains a linear regression model.
- Predicts salaries for the test set.
- Visualizes results with matplotlib.

