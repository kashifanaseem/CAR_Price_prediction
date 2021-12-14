# CAR_Price_prediction
#### Regression

## Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Feature Selection](#feature-selection)

**Introduction**: Prediction of price of used cars is required to give an estimation of the price to the buyer. Data to build predictive model was collected from cardekho.com.  Features are as follow:
* Car Name
* Year
* Selling Price
* Present Price
* Kms Driven
* Fuel Type 
* Seller Type
* Transmission 
* Owner

In all these **selling price** was target feature. Used RandomForest with RandomizedSearchCV to find best hyperperameters in order to achieve better accuracy.

**Technologies**: A few libraries and techs used in project
1. Jupyter notebook
2. Python 3.6
3. Pandas
4. Tensorflow 2.3.1
5. Matplot
6. seaborn

**Feature Selection**: To choose best features ExtraTreesRegressor was used with feature_importances_ function and chose 5 important features.
