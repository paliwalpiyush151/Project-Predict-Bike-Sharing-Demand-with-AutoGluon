# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Piyush Shri Tarachand Paliwal

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?

Five different kinds of model training experiments were performed on the data.
1. Initial Raw Submission
2. Adding more features and submission
3. Hyperparameter Optimization - Initial Setting Submission
4. Hyperparameter Optimization - Setting 1 Submission
5. Hyperparameter Optimization - Setting 2 Submission
   
I was able to make first submission from the raw data provided without any error while makeing submission of Exp.2,3,4,5, I got error during submission
since kaggle was not accepting negetive values. 

I made changes by assigning negetive values of prediction to zero. After this, I was able to make kaggle submission.

### What was the top ranked model that performed?
My top rae
## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Add your explanation

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|?|?|?|?|
|add_features|?|?|?|?|
|hpo|?|?|?|?|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](model_test_score.png)

## Summary
TODO: Add your explanation
