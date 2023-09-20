# Classification-models
analysis on assorted datasets using machine learning classification techniques
The Freud detection model uses Random Forrest as  first attempt as at creating a ML model for detecting fraud.
 Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
 The man issue with this data is we cannot possibly know what the original features were given the PCA transformation, and the data is highly imbalanced.
 I attempted using the SMOTE (Synthetic minority oversampling technique) to balance the data in the first attempt.
 This is a work in progess and I will be updating this current model and attempting many other classification techniques to achieve more consistent results.
