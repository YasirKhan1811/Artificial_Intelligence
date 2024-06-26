# Bias (Underfitting) and Variance (Overfitting)

- Bias: The inability of a machine learning method to capture the true relationship is called bias. For example, a straight line does not fit well with the curved relationship between
  two variables, so it has a high bias. However, the straight line shows low variance with the testing set. Hence, the straight line might not be great in predicting new data, but it is
  consistently better on new instances of data.
  
- Variance: The difference in fits between the data sets is called **Variance**. For example, a squiggle fits so well to the training set but has large residuals with the testing set.
  So, the squiggle hugs the training data so well that when it is tested on new or unseen data, sometimes it may give good predictions but most of the time it gives wrong
  predictions with the new data. The high variance between fitting to the training set and fitting to the testing set leads to **Model Overfitting**.

Three commonly used methods for finding the sweet spots between simple and complicated models are:
  - Regularization
  - Bagging
  - Boosting
