# Credit-Risk-Analysis
South German Credit data for the years 1973-1975 by UCI Machine Learning Repository is used for predicting the credit risk as either good or bad for the persons who have taken credit or loan from the banks. It contains a total of 1000 records. The ratio of good credit risk to bad credit risk records is 70:30.

This dataset contains 20 features and 1 target variable 'credit risk'. Out of the 20 features, there are 3 numerical features and 17 categorical features. Further, the 17 categorical features have 10 nominal and 7 ordinal features.

It's a binary classification problem. Initially, the good credit risk has label 1 and bad credit risk has label 0 in the dataset. But, since the aim of project is to classify the bad credit risk records correctly in order to reduce the losses caused by defaulters, the good credit risk records are replaced with label 0 and bad credit risk records are replaced with label 1.

The project starts off with some basic Data Transformations and then Exploratory Data Analysis (EDA) followed by Outlier Treatment. After that, Statistical Significance of features are checked using appropriate tests. Class Imbalance is handled using SMOTE. Feature Selection is performed using Recursive Feature Elimination (RFE) and Sequential Forward Selection (SFS) techniques before doing the modeling. Finally, various machine learning classification models are implemented. The model which gave the highest performance for the metrics 'recall' and 'precision' is chosen as the best model.



