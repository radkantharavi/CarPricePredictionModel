# CarPricePredictionModel

Data Source- https://www.kaggle.com/goyalshalini93/car-data

Target Variable- price

Predictors Used- 'wheelbase', 'enginesize', 'curbweight', 'carwidth', 'citympg', 'highwaympg', 'carlength', 'boreratio','horsepower'

AIM- Use price and markups on cars in existing dataset to build a model to predict price of a new car with given independent variables. 

Model Evaluation and Accuracy-

	**Random Forest**	**Ridge Regression**	**Ridge Regression CV**	**Lasso Regression**
R2		0.93			0.75			0.81			0.81
Adjusted R2	0.979			0.75			0.812			0.812
MAE		1528.79			2700.56			2390.01			2429.58
MAPE		12			21			20			20
![image](https://user-images.githubusercontent.com/61866486/152696648-ddc6053c-b471-4880-8221-940b7b23f796.png)


