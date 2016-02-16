# MachineLearning
Johns Hopkins Data Science course project - Machine Learning

This analysis uses data from a personal fitness monitor like Jawbone Up, Nike FuelBand or Fitbit. This analysis uses data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. In the study they were asked to perform barbell lifts correctly and incorrectly in 5 different ways. The machine learning goal is to predict the manner in which they did the exercise. This is the "classe" variable in the training dataset. 
The analysis partitions the training data reserving 30% of the observations for validation, fits six machine learning models using these methods

- Random forest
- Linear discriminant analysis (LDA)
- Naive Bayes
- K nearest neighbor (KNN)
- Gradient boosting machine (GBM)
- Recursive partitioning and regression tree (Rpart)

then chooses a model based on the lowest out of sample error rate to make the final predictions. 
A **random forest** model appears to be most accurate - with an out of sample error rate of about 0.5% - so it is used on the test set to predict values using predictors from the test set. Plots of the predictions and of variable importance for the chosen model are included in an appendix.

