# Assignment 1 :

## K-Nearest Neighbors (KNN):
1. Load the dataset 'iris.csv' using Pandas and split it into features (X) and target variable (y). How many features and target classes are there in the dataset? (Hint: Use Pandas functions)
2. Explain the concept of the KNN algorithm in your own words.
3. What is the significance of the parameter 'K' in KNN? How does it affect the algorithm's performance? (Hint: Consider the usage of NumPy arrays and scikit-learn's KNeighborsClassifier)
4. Split the dataset into training and testing sets using an 80:20 ratio. (Hint: Use scikit-learn's train_test_split)
5. Perform feature scaling on the training data using the StandardScaler from scikit-learn. (Hint: Utilize scikit-learn's StandardScaler)
6. Train a KNN classifier on the scaled training data with a chosen value of K. What is the accuracy of the model on the testing data? (Hint: Use scikit-learn's KNeighborsClassifier and accuracy_score)
7. How can you choose the optimal value of K for the KNN algorithm? Explain the process. (Hint: Consider using cross-validation or grid search techniques)

## Decision Tree:
1. Load the dataset 'titanic.csv' using Pandas and split it into features (X) and target variable (y). How many features and target classes are there in the dataset? (Hint: Use Pandas functions)
2. What is the concept of entropy in the context of decision trees? How is it calculated? (Hint: Consider the usage of scikit-learn's DecisionTreeClassifier)
3. Split the dataset into training and testing sets using a 70:30 ratio. (Hint: Use scikit-learn's train_test_split)
4. Train a decision tree classifier on the training data. What is the maximum depth of the tree? (Hint: Utilize scikit-learn's DecisionTreeClassifier)
5. Make predictions on the testing data using the trained decision tree model. (Hint: Use the predict() method of the DecisionTreeClassifier)
6. Calculate the accuracy, precision, and recall of the decision tree model. (Hint: Utilize scikit-learn's accuracy_score, precision_score, and recall_score)
7. How can you handle missing values in a dataset when using decision trees? (Hint: Consider scikit-learn's Imputer or Pandas' fillna methods)
8. Visualize the trained decision tree using the plot_tree() function from scikit-learn and Matplotlib. (Hint: Utilize scikit-learn's plot_tree and Matplotlib for visualization)
