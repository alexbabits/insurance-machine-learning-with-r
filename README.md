Predicting the insurance payouts based on customer features using R. Data used is Sample Insurance Claim Payments
</br>

Data was loaded from 'insurance.csv'. Categorical binary columns were converted to binary, region character/factors were one-hot encoded. Data was split 80/20 train/test randomly based on a distribution from the target column 'charges'.
</br>

Used Linear Regression, Random Forest, XGBoost, and LGBM.
</br>

Used Bayesian Optimization on the LGBM model to determin the best parameters.
</br>

For each model, plotted a Predictions vs Truth Chart and a Residuals Chart.
</br>

RMSE results: 
</br>

Linear Regression: 6369.24
</br>

Random Forest: 5232.83
</br>

XGBoost: 5164.75
</br>

LGBM: 5220.93

</br>

This data sample was extremely small and more of a comprehensive test/basic R refresher.


