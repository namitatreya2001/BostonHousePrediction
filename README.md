# Boston House Price Prediction

This project predicts the median value of homes in Boston using the **Boston Housing Dataset**, a classic dataset for regression tasks in machine learning.

## Dataset Overview

The Boston Housing dataset contains **506 instances** and **13 attributes** that are used as predictive features. The target variable is the **Median Value of owner-occupied homes** in $1000's.

### Dataset Features:
| **Feature**   | **Description**                                                                 |
|---------------|-------------------------------------------------------------------------------|
| **CRIM**      | Per capita crime rate by town                                                |
| **ZN**        | Proportion of residential land zoned for lots over 25,000 sq.ft.             |
| **INDUS**     | Proportion of non-retail business acres per town                             |
| **CHAS**      | Charles River dummy variable (1 if tract bounds river; 0 otherwise)          |
| **NOX**       | Nitric oxides concentration (parts per 10 million)                           |
| **RM**        | Average number of rooms per dwelling                                         |
| **AGE**       | Proportion of owner-occupied units built prior to 1940                       |
| **DIS**       | Weighted distances to five Boston employment centres                         |
| **RAD**       | Index of accessibility to radial highways                                    |
| **TAX**       | Full-value property-tax rate per $10,000                                     |
| **PTRATIO**   | Pupil-teacher ratio by town                                                  |
| **B**         | 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town      |
| **LSTAT**     | % Lower status of the population                                             |
| **MEDV**      | Median value of owner-occupied homes in $1000's (Target Variable)            |



---

## Project Details

The goal of this project is to **build and deploy a regression model** to predict house prices using the Boston Housing dataset.

### Workflow:
1. **Data Exploration & Preprocessing**:
   - Handle data visualization and statistics.
   - Scale features for optimal regression performance.

2. **Model Building**:
   - Train models using **scikit-learn**'s regression algorithms.
   - Compare model performances based on evaluation metrics such as RMSE and R² Score.

3. **Deployment**:
   - Use **Flask** as the backend server.
   - Deploy the model using **Gunicorn** and **Render**.

---

## Tech Stack

The following tools and libraries were used in this project:

- **Backend**: Flask
- **ML Libraries**: scikit-learn, pandas, numpy
- **Visualization**: matplotlib
- **Deployment**:  Render



