# Classification models in R
Training the classification models is accomplished with the Caret package in R. In addition, optimal values of hyper-parameters are estimated using 10-fold cross validation where the model is fitted to the nine-tenth of the training dataset and the performance of the model is measured using the remaining training data. 
1. This code is written in R to train machine learning models (specifically random forest, SVM, and lasso regression)
2. The code computes the performance of the model using unseen dataset
the code examines the effect of using PCA, which is used for dimensionality reduction, on the performance of the model
3. The code uses different methods to deal with imbalanced dataset
4. The code performs ordinal regression. This code be useful when there is an inherent ranking in the labels of data. 
5. A part of code assumes that the labels have unequal importance. In this case, the code wants to penalize the model if it misclassifies a special label.
