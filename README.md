# FIFA-19-Player-Value
FIFA19 Player Value Model and Predictions

[Link to this project on Kaggle](https://www.kaggle.com/yuankunsong/fifa19-predicting-the-value-of-players)

## In this project I tried to build a model to explain and predict the "Value" of a soccer player given his attributes, initially I build models using traditional regression methods:
* Ordinary Least Squares
* Ridge Regression
* LASSO Regression
* Elastic Net

## Later on I used a relatively new method:
* XGBoost

XGBoost out performed all the regression models earlier. In the end I took a closer look at the XGBoost model and attempt to find out which attributes are more important in determining a player's value.

### A breif look at the values by players at different position

![alt text](https://github.com/charliesong66/Charlie_Song_DataScience_Portfolio/blob/master/images/fifa19%20player%20value.png?raw=true)

### Feature importance given by the XGBoost model
![alt text](https://github.com/charliesong66/Charlie_Song_DataScience_Portfolio/blob/master/images/fifa19%20feature%20importance.png?raw=true)
