# Penalized-Regression-Machine-Learning

## About the Dataset
- Purpose: The dataset is used to study penalized regression techniques in a supervised learning context.
- Nature: Includes features for regression modeling with potential multicollinearity, making it suitable for techniques like Ridge and Lasso regression.
- Focus: Identifies predictors with the most significant impact on a target variable while managing overfitting and improving model interpretability.

## What I Did in the Project
- Exploratory Data Analysis: Conducted data cleaning and preprocessing to ensure the dataset was ready for modeling.
- Feature Selection: Evaluated and selected significant predictors to reduce noise and improve model performance.
- Penalized Regression Techniques: Implemented Ridge and Lasso regression to manage multicollinearity and optimize predictive power.
- Hyperparameter Tuning: Used cross-validation to fine-tune regularization parameters for both Ridge and Lasso regression models.
- Model Evaluation: Compared model performance using metrics like Mean Squared Error (MSE) and R-squared to assess predictive accuracy.
- Interpretability: Visualized coefficient shrinkage and predictor importance to demonstrate the effects of regularization.

### Correlation Matrix. This will help determine which variables are the most or less important.
![](https://github.com/anaiscorral/Pernalized-Regression-Machine-Learning/blob/main/p%20regression.png)

### AUC Ridge & Lasso Comparisson.
In this case, models (Lasso and Ridge) are performing well, since their AUC values are close to 1, which indicates strong predictive power.
This means that the model can correctly identify who will say “yes” and who will say “no” to the campaign (separating customers who accepted the campaign, from those who didn’t).

![](https://github.com/anaiscorral/Pernalized-Regression-Machine-Learning/blob/main/p%20regression%202.png)

![](https://github.com/anaiscorral/Pernalized-Regression-Machine-Learning/blob/main/p%20regression%203.png)
