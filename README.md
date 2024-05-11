# Breast_Cancer_Dataset_analysis

We explored the Breast Cancer data and implemented various classification algorithms. We started by
implementing PCA and best subset selection techniques to try and reduce the number of predictor variables.
We also tried to add regularization to the Logistic Regression by adding LASSO penalty, however it did
not result in removal of any predictor variables, just shrinkage of less important coefficients. Finally, we
implemented QDA with best subset selection technique. To assess the performance of all these models, we
tried cross validation based on test errors. Logistic Regression with LASSO penalty has the smallest test
error, and a close second is Logistic Regression using PCA. We concluded that Logistic Regression with
LASSO penalty is the best classifier, even though it has all the predictor variables.
