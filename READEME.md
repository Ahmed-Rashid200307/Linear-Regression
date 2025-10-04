# Simple Linear Regression Project

This project demonstrates simple linear regression using Python and scikit-learn. It includes Jupyter notebooks for experimenting with regression on sample datasets and visualizing results.

## Project Structure

- `intro.ipynb`: Introduction to linear regression with a simple example dataset.
- `lg2.ipynb`: Linear regression analysis on the `StudentsPerformance.csv` dataset.
- `StudentsPerformance.csv`: Dataset containing student scores and demographic information.
- `.gitignore`: Git ignore file (ignores PNG images and itself).
- `download.png`, `download (1).png`: Example images (ignored by git).

## Requirements

- Python 3.12+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- scikit-learn

## Usage

1. Install dependencies:
    ```sh
    pip install pandas numpy matplotlib scikit-learn jupyter
    ```

2. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

3. Open and run `intro.ipynb` or `lg2.ipynb` to explore linear regression examples.

## Notebooks Overview

- **intro.ipynb**:  
  - Creates a synthetic dataset.
  - Splits data into train/test sets.
  - Fits a linear regression model.
  - Evaluates and visualizes the regression line.

- **lg2.ipynb**:  
  - Loads and explores the `StudentsPerformance.csv` dataset.
  - Performs regression analysis using student scores.
  - Visualizes relationships between scores.

## License

This project is for educational purposes.