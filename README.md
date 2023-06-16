**Predicting the insurance payouts based on customer features using R. Data used is Sample Insurance Claim Payments**
</br>
</br>
</br>
Data was loaded from 'insurance.csv'. Categorical binary columns were converted to binary, region character/factors were one-hot encoded. 
</br>
</br>
Data was split 80/20 train/test randomly based on a distribution from the target column 'charges'.
</br>
</br>
Used Linear Regression, Random Forest, XGBoost, and LGBM.
</br>
</br>
Used Bayesian Optimization on the LGBM model to determin the best parameters.
</br>
</br>
For each model, plotted a Predictions vs Truth Chart and a Residuals Chart.
</br>
</br>
RMSE results:
</br>
</br>
<img src="Pictures\RMSE by Model.png">
</br>
</br>
**Linear Regression: 6369.24**
</br>
</br>
<img src="Pictures\Lin Reg.png">
<img src="Pictures\Lin Reg Residuals.png">
</br>
</br>
**Random Forest: 5232.83**
</br>
</br>
<img src="Pictures\RF.png">
<img src="Pictures\RF Residuals.png">
</br>
</br>
**XGBoost: 5164.75**
</br>
</br>
<img src="Pictures\XGBoost.png">
<img src="Pictures\XGBoost Residuals.png">
</br>
</br>
**LGBM: 5220.93**
</br>
</br>
<img src="Pictures\LGBM.png">
<img src="Pictures\LGBM Residuals.png">
</br>
</br>
***LGBM Bayesian Optimization (0.2 learning rate, 5 num leaves)***
</br>
</br>
<img src="Pictures\LGBM Bayesian Optimize.png">
