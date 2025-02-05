# WhatDrivesThePriceOfACar

[Link to codelab](what_drives_the_price_of_a_car.ipynb)

## Business Understanding 
The question that we want to answer is "What factors make a car more or less expensive?". To create an estimation model that answers this question we first need to get datasets that contain the vehicle price information and multiple features associated to it. We will use the "vehicles.csv" dataset. Then we will understand, prepare, and model the data to answer which features, and their weights, drive the price of vehicles.

## Deployment
In the model evaluation table we can see that the model with the highest R2 Score is "Model with Mode Values, One Hot Encoder, James Stein Encoder, and Standard Scaler". Still it is important to explain to the customer that this model only explains 43.9% of the price.

If we study the models features and coefficients we can see that the price is mostly driven negatively by region/state, type, and title status. Coupe and "other" types of cars reduce the price. Also regions like Columbia, Florence, Baton, sell cars at lower prices. The status of the title if it's lien or missing also reduces the price. The price is mostly driven positiely by region and manufacturer. The price will be higher if it comes from manufacturers like Ferrari, Aston Martin, Tesla, Datsun, and Porcsche. The price will be higher if the vehicle is sold in regions like Louisville, Western KY, Bowling Green, Lexington, Owensboro, and Eastern Kentucky.
