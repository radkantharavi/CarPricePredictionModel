# CarPricePredictionModel

Data Source- https://www.kaggle.com/goyalshalini93/car-data

Target Variable- price

Predictors Used- 

AIM- Understand existing patterns around Hotel Bookings getting cancelled and build a predictive model to understand if a new booking is likely to cancelled/not and the factors impacting such an event as well.

Metadata- https://www.sciencedirect.com/science/article/pii/S2352340918315191

Model Evaluation and Accuracy-

**Model Name**	         **Accuracy**	**Run time**
Random Forest	               0.80	      0.56
Artificial Neural Network      0.77	      88.8
KNN	                       0.76	      617.47
Logistic Regression	       0.73	      7.16
Decision Tree	               0.63	      0.42
Recommendations-

Based on the above analysis the best predictive model to use is Random Forest with a model accuracy of 80%
Change how booking is offered: The company must focus on using this model to change how hotel reservations are offered to a candidate. The booking page has to first take in customer details through profile creation so that the necessary data is available to run this model on. This can be optimized collecting only the model predictors needed to run the analysis and used to make offers to our customer in a way they won't cancel the booking later. The rest of the cold storage data can be collected after the booking is completed too.
Change marketing strategies : a- Top 5 revenue countries are PRT, GBR, ESP, FRA, DEU . There can be more focus on the booking efforts here. b- There is no one specific marketing channel that works, different methods for each country will have to be used as per the data analysis. c- TA/TO channel is most used for making bookings. d - Resort hotels are least booked every year, so these need more marketing. e- Transient type customers make the highest bookings for both resorts and city hotels and has a strong revenue potential.
