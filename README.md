# CS-422-Course-Project

# Concrete Compressive Strength Prediction

## Problem Statement
This project aims to predict the compressive strength of concrete through machine learning models. Concrete compressive strength is an important indicator for building material design and construction safety. Accurate prediction helps optimize material ratios, reduce costs and ensure structural safety.

## Key Findings
- Through data standardization and linear regression model, the model is able to capture the feature relationships that mainly affect the compressive strength of concrete.
- The prediction results on the test set show that the model has a certain predictive ability, but there are still errors, indicating that the model has not yet reached the best performance.

## Model Performance
- Mean Square Error (MSE): about 95.98
- Root Mean Square Error (RMSE): about 9.80
- Coefficient of Determination (R²): about 0.63

These indicators show that the linear regression model can explain about 63% of the variability in the data, but the prediction error is large, suggesting that further optimization is needed.

## Future Improvement Directions
- Perform more detailed feature engineering, including generating new features or using feature selection techniques
- Use cross-validation and hyperparameter tuning to optimize model parameters and reduce overfitting and underfitting.
- Explore data augmentation or collect more samples to improve the generalization ability of the model.
