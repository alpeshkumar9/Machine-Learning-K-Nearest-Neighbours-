###  Implemented ML algorithms with the neural networks, SVM, & cross-conformal prediction algorithms

1. Load the data set into Python using, e.g., load_wine or genfromtxt, as appropriate. In the case of the USPS dataset, merge the original training and test sets into one dataset.
2. Divide the dataset into a training set and a test set. You may use the function train_test_split. Use your birthday in the format DDMM as random_state (omit leading zeros if any).
3. Using cross-validation and the training set only, estimate the generalization accuracy of the MLPClassifier with the default values of the parameters. You may use the function cross_val_score.
4. Get rid of the warnings by varying a parameter, or parameters, such as max_iter. Estimate the generalization accuracy of the MLPClassifier with the modified values of the parameters. (If there are no warnings, the modified values of the parameters may be identical to the default values.)
5. Find the test error rate of the MLPClassifier with the modified values of parameters, compare it with the estimate obtained in the previous task
(task 4) for the same values of parameters, and write your observations in a markdown cell of your Jupyter notebook.
6. Create a pipeline for MLPClassifier involving data normalization and MLPClassifier, and use grid search and cross-validation to tune parameter alpha for the pipeline, avoiding data snooping and data leakage. You may use the scikit-learn class GridSearchCV. Experiment with different ways of doing normalization (such as StandardScaler, MinMaxScaler,
RobustScaler, and Normalizer). Which ways are appropriate for either 2 dataset? (The answer, which should be written in your Jupyter notebook, may depend on the results that you obtain for the next task.)
7. Fit the GridSearchCV object of task 6 to the training set and use it to predict the test labels. Write the resulting test error rate in your Jupyter notebook.
