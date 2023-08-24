# HousePrice Regression
*Tools used: Python, Tensorflow, Matplotlib, Stacked Regression, Data Exploration, Data Visualisation, Lasso, XGBR, LGBM*
### Description
In this project, I used US housing data to predict housing prices. I started with an extensive Explorative Data Analysis where I identified the important features, cleaned the data and created new more significant features from existing features. For the modelling, I used two different approaches:
* Tensorflow decision trees
* Stacking several regression models (GradientBoostingRegression, XGBR Regressor, LGBM Regressor, Lasso, Enet, Kernel Ridge Regressor )

Both the Tensorflow decision tree and the stacked regression lead to good results of a root-mean-square error (RMSE) of:

**RMSE=0.07**

More details can be found in the [notebook](https://github.com/jcwons/HousePrice_Regression/blob/main/eda-stacking-and-tensorflow-decision-trees.ipynb).

