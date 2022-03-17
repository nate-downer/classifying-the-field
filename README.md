# Classifying the Field
A collection of algorithms for predicting the outcome of F1 races.

##Abstract
This report explores the extent to which it is possible to model the finishing order of a Formula One race using two different classification models. Due to the amount of randomness inherent to motor racing, modeling a race’s outcome based on the drivers’ past performance is incredibly difficult to do. Ultimately, this report will show that both Logistic Regression, and Neural Network models are not able to reliably outperform baseline predictors when making predictions for an individual race. Instead, what these machine learning techniques are able to do is model a driver’s performance over the course of a season. While these models cannot accurately predict who will have a bad race on a given day, they are able to predict who will have more bad days across a number of races. 

Additionally this report evaluates how well the predictions of the trained models stack up against actual Formula One fans. By simulating all of the models predictions for the 2021 season, and comparing them to the predictions submitted to the “Back of the Grid” podcast’s predictions league, this report further demonstrates these models' weakness at predicting specific outcomes.

##Data
Most of the data is sourced from [this wonderful dataset](https://www.kaggle.com/rohanrao/formula-1-world-championship-1950-2020) on kaggle, with additional data scrubbed from F1's website.
