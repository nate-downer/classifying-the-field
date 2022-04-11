# Classifying the Field
A collection of algorithms for predicting the outcome of F1 races. If you want the full analysis, you can read the Final Report [here](https://github.com/nate-downer/classifying-the-field/blob/main/Classifying%20the%20Field%20-%20Final%20Report.pdf).

For a look at how the predictabillity of F1 races has changed over time, check out [this in depth visualization](https://public.tableau.com/app/profile/nate.downer/viz/FormulaOne-PredictabilityOverTime/Dashboard1#1).

## Abstract
This report explores the extent to which it is possible to model the finishing order of a Formula One race by using two different classification models. Due to the amount of randomness inherent to motor racing, modeling a race’s outcome based on the drivers’ past performance is incredibly difficult. Ultimately, this report will show that both Logistic Regression, and Neural Network models are not able to reliably outperform baseline predictors when projecting the full finishing order for an individual race. Instead, these machine learning methods are better suited to modeling a driver’s performance over the course of a season. While these models cannot accurately predict who will have a bad race on a given day, they are able to predict who will have more bad days across a number of races. 

Additionally this report evaluates how well the predictions of the trained models stack up against actual Formula One fans. By simulating all of the models’ predictions for the 2021 season, and comparing them to the predictions submitted to the “Back of the Grid” podcast’s predictions league, this report further demonstrates these models' weakness at predicting the outcomes of specific races.

## Data
Most of the data is sourced from [this wonderful dataset](https://www.kaggle.com/rohanrao/formula-1-world-championship-1950-2020) on Kaggle, with additional data scrubbed from [F1's website](https://www.formula1.com/en/results.html).

The data used to compare the models' predictions to guesses made by actual people was scrubbed from the [Back of the Grid website](https://backofthegrid.com/prediction-results#).

## A Note on Predictability
![alt text](https://github.com/nate-downer/classifying-the-field/blob/main/predictability-dashboard.png?raw=true)
