# SC1015 Car Price Prediction
![Alt text](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/img.png)

## Introduction
***
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) 2023. We will be predicting car price based on different features of a car. The dataset which we are using is [car_sales.csv](https://www.kaggle.com/datasets/smritisingh1997/car-salescsv?topic=internetDataset) from [Kaggle](https://www.kaggle.com).  <br />

_**Disclaimer: Individual Codes do not work separately, it is merely for easy-viewing of separate sections.**_  <br />
For a detailed walkthrough please view the source code in order: 
1. [Data Importation & Description](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/Data%20Importation%20%26%20Description.ipynb)
2. [Data Pre-processing](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/Data%20Pre-processing.ipynb)
3. [Exploratory Data Analysis & Visualisation](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/Exploratory%20Data%20Analysis%20%26%20Visualization.ipynb)
4. [Methodology](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/Methodology.ipynb)
5. [Experiments](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/Experiments.ipynb)
6. [Conclusion](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/Conclusion.ipynb)

OR<br />
View the [Whole Code](https://github.com/skylimm/SC1015-Car-Price-Prediction/blob/main/Car%20Prediction.ipynb)  <br />


_**Disclaimer: This notebook is best viewed using Jupyter Notebook or Visual Studio Code.**_


## Contributors
***
- @skylimm (Sky Lim En Xing) - Data Pre-processing, Models, Slides, Github Integration & Model Analysis 
- @HollowGale (Thomas Tan Keat Hao) - Model Analysis, Video Presentation, Slides & Exploratory Data Analysis
- @... (Chermine Cheah Xue Min) - Data Importation, Description, Exploratory Data Analysis & Visualization


## Problem Definition
- How do we predict prices using different features of a car to help budget-conscious car-buyers ?
***

## Models Used
***
1. Linear Regression (BaseLine Model)
2. Lasso
3. Gradient Regressor Booster
4. Ridge Regression


## Conclusion
***
1) Using different machine learning models, we are able to predict car prices based on different features of a car.
  * Gradient Boosting Regression is the best model out of the 4 available models to predict car prices based on each feature of a car.
  * Gradient Boosting Regression has a 0.9/1.0 for R², an almost perfect score for its predictive capabilities.
2) Most of our regression models are decently accurate and predictive and can help carbuyers make an accurate estimation of any car's price.
  * However, all our regression models do suffer some overfitting of data.
  * We can use Lasso and Ridge Regression models in conjunction with Gradient Boosting Regression to offset some overfitting of data through a process called Regularisation.


## What did we learnt from this project?
***
- Basic exploratory analysis using numpy and pandas.
- Data visualisation techniques via Seaborn and Matplotlib libraries.
- Data engineering via cleaning (IQR technique) and transforming raw data (StandardScaling, Data Conversion) to allow our data to be more easily used for machine learning models.
- Data encoding techniques (e.g. OneHot and Label encoding) to convert categorical data to usable inputs for machine learning models
- Importance of parameters in Regression Models' functionality, and how to optimise it through HyperTuning
- Efficient hyptertuning through the implementation of GridSearch


## References
***
car_sales.csv. (2020, May 9). Kaggle. https://www.kaggle.com/datasets/smritisingh1997/car-salescsv
https://www.kaggle.com/code/smritisingh1997/car-price-prediction-using-linear-regression/input

Team, D. (2022). "Lasso and Ridge Regression in Python Tutorial." https://www.datacamp.com/tutorial/tutorial-lasso-ridge-regression

Bhattacharyya, S. (2023, February 22). "Ridge and Lasso Regression: L1 and L2 Regularization." Medium. https://towardsdatascience.com/ridge-and-lasso-regression-a-complete-guide-with-python-scikit-learn-e20e34bcbf0b

Trinidad, C. (2023). "Gradient Boosting." Corporate Finance Institute. https://corporatefinanceinstitute.com/resources/data-science/gradient-boosting/

sklearn.ensemble.GradientBoostingRegressor. (n.d.). Scikit-learn. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html

sklearn.linear_model.Lasso. (n.d.). Scikit-learn. https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html#sklearn.linear_model.Lasso

sklearn.linear_model.Ridge. (n.d.). Scikit-learn. https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html#sklearn.linear_model.Ridge

sklearn.linear_model.LinearRegression. (n.d.). Scikit-learn. https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html

"Choosing the right estimator." (n.d.). Scikit-learn. https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html

Smritisingh. (2020). "Car Price Prediction Using Linear Regression." Kaggle. 

Healy, Y. H. a. C. (n.d.). From data to Viz | "Find the graphic you need." https://www.data-to-viz.com

"How to find optimal parameters using GridSearchCV for Regression in ML in python" -. (2023, January 19). ProjectPro. https://www.projectpro.io/recipes/find-optimal-parameters-using-gridsearchcv-for-regression

Great Learning Team. (2022, June 13). "Hyperparameter Tuning with GridSearchCV" https://www.mygreatlearning.com/blog/gridsearchcv/#:~:text=What%20is%20GridSearchCV%20used%20for,essentially%20a%20cross%2Dvalidation%20technique

Acharya, S. (2022, January 6). "How to improve the accuracy of a Regression Model - Towards Data Science." Medium. https://towardsdatascience.com/how-to-improve-the-accuracy-of-a-regression-model-3517accf8604
