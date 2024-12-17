# Data Preparation and Analysis
Python assignments for the IIT CSP571 course

## Assignment 1: Linear Regression and Regularization
Here the UCI ML Automobile dataset (https://archive.ics.uci.edu/dataset/10/automobile) is used to perform basic linear regression using the scikit-learn linear_model module. Ridge and Lasso regularization is also applied with different lambda values and the performance is compared. The PolynomialFeatures module is also used to study a possible non-linear relationship.

## Assignment 2: Data Visualization
In this assignment the goal was to apply different visualization techniques to the same Automobile dataset in order to gain insight and find out relations between the features. Five distinct visualization techniques were used.

## Assignment 3: Tree-based classification, feature reduction (PCA) and clustering
In this assignment the UCI ML Heart Disease dataset (https://archive.ics.uci.edu/dataset/45/heart+disease) was used to apply tree-based classification, feature reduction and clustering techniques. For the tree-based classification models, the scikit-learn modules DecisionTreeClassifier and RandomForestClassifier were used, and boosting was also applied using xgboost. The three resulting models were then compared. For the next part, PCA was used for feature reduction which allows to visualize the clusters in the data, and then a manual implementation of K-Means as well as scikit-learn SpectralClustering is applied. Their performances are also analysed.
