# TitanicKaggleSubmissions

Several attempts have been made to deveop models to train on the titanic train data (from train.csv) and predit from the test data (from test.csv).

The current attempt to solve the problem assumes fields such as fares have high variability, and others such as Passenger ID, and Ticket are irrelevant, and Cabin Number or Fare are redundant and may be better represented by PClass. 

Categorical variable, sex is converted to binary, and Embarked is One-Hot Encoded. Stochastic Gradient Descent, Support Vector Machines, Random Forests, K Nearest Neighbors, and Decision Trees models are trained and evaluated.
