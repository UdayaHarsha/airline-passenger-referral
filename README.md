# Airline-Passenger-Referral

## Context:
Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choices and free text questions. Data is scrapped in Spring 2019.

## Object :
bold textThe main object is predict whether the passengers will refer the airline to their friends.

## Descriptions :
airline: Name of the airline.

overall: Overall point is given to the trip between 1 to 10.

author: Author of the trip

review date: Date of the Review

customer review:Review of the customers in free text format

aircraft: Type of the aircraft

traveller type: Type of traveler (e.g. business, leisure)

cabin: Cabin at the flight date flown: Flight date

seat comfort: Rated between 1-5

cabin service: Rated between 1-5

foodbev: Rated between 1-5

entertainment: Rated between 1-5

ground service: Rated between 1-5

value for money: Rated between 1-5

recommended: Binary, target variable.

## Conclusion:
The Models used for this Classsification problem are

1.Logistic Regression Model

2.Decision Tree Model

3.Random Forest Model

4.K-Nearest Neighbor Model

5.Support Vector Machine,

### Accuracy of each model:

94% accuracy with Logistic Regression,

92% accuracy with Decision Tree Model,

93% accuracy with Random Forest model,

93% accuracy with K-Nearest Neighbor Model,

93% accuracy with Support Vector Machine,

Even though all the models gave ccuracy rate above 90%, Logistic regression is sligtly more accurate than other models. Hence for this, Logistic Regression is best model.

Overall rating and Value for money contributes to a model's prediction whether a passenger will recommened a particular airline to their friends.

As a result, in order to increase their business or grow, our client must provide excellent cabin service, ground service, food beverage entertainment, and seat comfort as these contribute to overall rating and value for money rating.
