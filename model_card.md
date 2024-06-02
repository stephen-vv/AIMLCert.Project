# Model Card

## Model Description

**Input:** Describe the inputs of your model 

The model takes in the following features from the Titanic dataset:

Pclass: Ticket class (1st, 2nd, or 3rd)
Sex: Gender (encoded as 0 for male and 1 for female)
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Fare: Passenger fare
Embarked: Port of embarkation (encoded as 0 for Southampton, 1 for Cherbourg, and 2 for Queenstown)

**Output:** Describe the output(s) of your model

The model outputs a binary classification:

0: Did not survive
1: Survived

**Model Architecture:** 

The model used is a Random Forest classifier. Random Forest is an ensemble learning method that constructs multiple decision trees during training and outputs the mode of the classes (classification) of the individual trees.

## Performance

When measuring performance on the training data,
Confusion Matrix:
 [[545   4]
 [ 14 328]]

Accuracy:  0.9797979797979798
Specificity:  0.9927140255009107

## Limitations

- Overfitting: The model was evaluated on training data which could lead to risk of overfitting.
- Data imbalance: The dataset has more non-survivors which could affect predictive performance of the minority result.

## Trade-offs

- Interpretability: Random forest models are powerful but lack interpretability when compared with more simple classifiers like logistic regression, for example.

