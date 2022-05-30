### Lasso ML Algorithm, data preprocessing, and tools for parameter selection in scikit-learn

1. Loaded the scikit-learn version of the diabetes dataset into Jupyter notebook using the load_diabetes function.
2. Splitted the dataset into the training and test sets using the function train_test_split in scikit-learn.
3. Found the training and test R2 for the Lasso model using the default
parameters.
4. Loaded the original diabetes dataset. 
5. Splitted the dataset into the training and test sets.
6. Computed the difference between both the datasets.
7. Preprocessed the training and test sets in the same way and preventing data snooping using StandardScaler.
9. Using different values of the parameter α in the Lasso, plotted the test R2 vs the number of features used (i.e., those with non-zero coefficients).
10. Chose the regularization parameter for the Lasso using cross-validation on the training set. Trained the Lasso on the whole training set using the
chosen values of the parameters.
