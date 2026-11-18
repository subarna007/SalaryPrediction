# Salary Prediction with Regression

Predicts salary from age, years of experience and education level using the Salary Data
dataset (375 rows: age, gender, education level, job title, years of experience, salary).

## Notebooks

| Notebook | What it covers |
|---|---|
| `Salary Prediction.ipynb` | Data preparation for simple regression: salary vs years of experience |
| `Salary Prediction using Regression.ipynb` | Simple linear regression with train/test plots and a prediction for 5 years of experience |
| `Multivarient_SalaryPrediction.ipynb` | Multiple linear regression with age, experience and one-hot encoded education |

## Result (multiple regression)

The data is split 85% train and 15% test. On the test split:

- R² = 0.920
- Mean absolute error = 10,158 (salary units of the dataset)

## Run it

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```
