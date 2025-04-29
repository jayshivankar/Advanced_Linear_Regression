# Ridge and Lasso Regression on California Housing Data

This project demonstrates the application of **Ridge Regression** and **Lasso Regression** on the California Housing dataset. The goal is to predict median house values based on various features using regularized linear models and compare their performance.

---

## 📊 Dataset

We use the **California Housing dataset** provided by `sklearn.datasets`.

```python
from sklearn.datasets import fetch_california_housing
data = fetch_california_housing()

Features:
MedInc: Median income

HouseAge: Median house age

AveRooms: Average number of rooms

AveBedrms: Average number of bedrooms

Population: Block group population

AveOccup: Average house occupancy

Latitude, Longitude

Target:
MedHouseVal: Median house value for California districts (in $100,000s)

🧪 Models Applied
1. Ridge Regression
Penalizes large coefficients using L2 regularization

Helps prevent multicollinearity and overfitting

2. Lasso Regression
Uses L1 regularization, which can shrink coefficients to zero

Useful for feature selection

⚙️ Implementation Overview
Data pre-processing using StandardScaler

Train-test split using train_test_split

Model training with RidgeCV and LassoCV for hyperparameter tuning

Evaluation using R² score and Mean Squared Error (MSE)


Features:
MedInc: Median income

HouseAge: Median house age

AveRooms: Average number of rooms

AveBedrms: Average number of bedrooms

Population: Block group population

AveOccup: Average house occupancy

Latitude, Longitude

Target:
MedHouseVal: Median house value for California districts (in $100,000s)

🧪 Models Applied
1. Ridge Regression
Penalizes large coefficients using L2 regularization

Helps prevent multicollinearity and overfitting

2. Lasso Regression
Uses L1 regularization, which can shrink coefficients to zero

Useful for feature selection

⚙️ Implementation Overview
Data pre-processing using StandardScaler

Train-test split using train_test_split

Model training with RidgeCV and LassoCV for hyperparameter tuning

Evaluation using R² score and Mean Squared Error (MSE)

| Model  | R² Score | MSE      |
|--------|----------|----------|
| Ridge  | ~0.60    | (value)  |
| Lasso  | ~0.60    | (value)  |
