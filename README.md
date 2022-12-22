# BHMLAI Practical Application 11.1

The link to the notebook: 

The conclusions of this practical application.

The declared purpose of this analysis was to determine the features which influence the price of used cars the most. The second purpose was to create a prediction model to be used for predicting the price of the used car using the above features.

The most important features that influence the price of a used car are:
- age
- mileage
- car type,
- manufacturer
- type of drive
- cylinders
- fuel

The model we created has a score of 0.88 with minimal median absolute error, both of which make the model very solid and recommended for use.

Newer diesel sedan cars, with lower mileage, forward drive and a serious engine / more cylinders sell for most money.

Sedans, SUV's and pickups sell for more money so the inventory must include these.

Toyota, Chevrolet, Ford, Lexus, Jeep and Mercedes should be the top choices for your inventory, especially sedans and SUVs.

The county where the dealership is located matters for the price. Same car sells for more in some counties. We can provide at your request the distribution of average price per county.

Convertibles, mini-vans, wagons are not selling for much.



Next steps and recommendations:

Try to do separate analysis for each state in part, pay attention to the regions/counties and make a recommendation on which county drives higher sales and price in that state.

The data does not include the acquisition cost for each car, so the profit made is not visible. Even if the car sells for more money due to various combinations of features, the profit can be smaller than for cars that sell for less amounts. A future activity should be collecting the cost or profit per car sold so we can analyze what features influence the profit per car sold.

The inventory dynamics are not captured in the data, such as the time a car stays on the lot, which is an important metric for dealerships. Future activity should be collecting such additional data.

The car model data as is collected now is not very practical for analysis. There are too many variations and too many details in the model. We determined that the initial data set had 29k unique models, and this was because of the way the model was entered. A future activity should be to standardize the model data and move the additional details into separate data to be used as features in analysis.
