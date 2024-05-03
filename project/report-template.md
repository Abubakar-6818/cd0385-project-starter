# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### ABUBAKAR ABUBAKAR AL-AMIN

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
I my predictions no were needed because all of my predictions were > 0

### What was the top ranked model that performed?
The top ranked model was  WeightedEnsemble_L3 with score_val of -53.126572 and pred_time_val, fit_time, pred_time_val_marginal, fit_time_ of  21.491584, 368.646480, 0.000702 and 0.065879 respectively

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
I my exploratory data analysis created a histogram of all features to show the distribution of each one relative to the data.
I added new features by seprating the "datetime" column in year, month, day and hour

### How much better did your model preform after adding additional features and why do you think that is?
The model score_val ,pred_time_val, fit_time, pred_time_val_marginal, fit_time_ became -30.353867, 25.945842, 361.508742, 0.000889, 0.036304 respectively.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
The model score_val , pred_time_val, fit_time, pred_time_val_marginal, fit_time_ became -34.869666, 6.391285,  118.907295, 0.000630, 0.030676

### If you were given more time with this dataset, where do you think you would spend more time?
I will spend more on the hyper parameter tuning

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|initial|?|?|?|?|
|add_features|?|?|?|?|
|hpo|?|?|?|?|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
