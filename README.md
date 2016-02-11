# Practical Machine Learning Final Project: Predicting Human Activities from Weight Lifting Exercise

This report aims to predicts human activities from the Weight Lifting Exercise Dataset. Cleaning the dataset resulted in 52 features used to predict the activity class (classe), 19,622 observations for the training and validation sets (split 60/40) and 20 observations for the test set. We perform random forest classification, boosted general linear model, support vector machine, and a stacked model of all above on the training dataset using random forest classification. As a result, the stacked model has the highest accuracy rate of 99.16% (validation). However, considering the complexity tradeoff, we opt for the random forest model with accuracy rate of 99.11% (validation).

You can see the html version [here](http://cstorm125.github.io/machine_final/).
