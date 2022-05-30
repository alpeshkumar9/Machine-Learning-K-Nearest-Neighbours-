###  Implemented ML algorithms with the neural networks + SVM algorithms

1. Loaded the data set into Python using load_wine or genfromtxt, as appropriate. In the case of the USPS dataset, merged the original training and test sets into one dataset.
2. Divided the dataset into a training set and a test set. Used the function train_test_split.
3. Using cross-validation and the training set only, estimated the generalization accuracy of the MLPClassifier with the default values of the parameters.  Used the function cross_val_score.
4. Got rid of the warnings by varying a parameter, or parameters, such as max_iter. Estimated the generalization accuracy of the MLPClassifier with the modified values of the parameters.
5. Generated the test error rate of the MLPClassifier with the modified values of parameters, compared it with the estimate obtained in the previous task for the same values of parameters.
6. Created a pipeline for MLPClassifier involving data normalization and MLPClassifier, and used grid search and cross-validation to tune parameter alpha for the pipeline, prevented data snooping and data leakage. Used the scikit-learn class GridSearchCV.
