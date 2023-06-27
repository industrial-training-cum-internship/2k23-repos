# Assignment 1 :

## K-Nearest Neighbors (KNN):
1. Load the dataset 'iris.csv' using Pandas and split it into features (X) and target variable (y). How many features and target classes are there in the dataset? 
    (Hint: Use `Pandas` functions)
2. Explain the concept of the KNN algorithm in your own words.
3. What is the significance of the parameter 'K' in KNN? How does it affect the algorithm's performance? 
    (Hint: Consider the usage of NumPy arrays and scikit-learn's `KNeighborsClassifier`)
4. Split the dataset into training and testing sets using an 80:20 ratio. (Hint: Use scikit-learn's train_test_split)
5. Perform feature scaling on the training data using the StandardScaler from scikit-learn. (Hint: Utilize scikit-learn's StandardScaler)
6. Train a KNN classifier on the scaled training data with a chosen value of K. What is the accuracy of the model on the testing data? 
    (Hint: Use scikit-learn's `KNeighborsClassifier` and `accuracy_score`)
7. How can you choose the optimal value of K for the KNN algorithm? Explain the process. 
    (Hint: Consider using `cross-validation` or grid search techniques)

## Decision Tree:
1. Load the dataset 'titanic.csv' using Pandas and split it into features (X) and target variable (y). How many features and target classes are there in the dataset? 
    (Hint: Use Pandas functions)
2. What is the concept of entropy in the context of decision trees? How is it calculated? 
    (Hint: Consider the usage of scikit-learn's `DecisionTreeClassifier`)
3. Split the dataset into training and testing sets using a 70:30 ratio. (Hint: Use scikit-learn's train_test_split)
4. Train a decision tree classifier on the training data. What is the maximum depth of the tree? 
    (Hint: Utilize scikit-learn's `DecisionTreeClassifier`)
5. Make predictions on the testing data using the trained decision tree model. (Hint: Use the predict() method of the DecisionTreeClassifier)
6. Calculate the accuracy, precision, and recall of the decision tree model. 
    (Hint: Utilize scikit-learn's `accuracy_score`, `precision_score`, and `recall_score`)
7. How can you handle missing values in a dataset when using decision trees? 
    (Hint: Consider scikit-learn's Imputer or Pandas' fillna methods)
8. Visualize the trained decision tree using the `plot_tree()` function from scikit-learn and Matplotlib. 
    (Hint: Utilize scikit-learn's `plot_tree` and Matplotlib for visualization)

## Support Vector Machines (SVM):
1. Load the dataset 'breast_cancer.csv' using pandas and split it into features (X) and target variable (y). How many features and target classes are there in the dataset?
  ( Hint: Check the shape of the DataFrame using `df.shape`.)

2. Explain the intuition behind the Support Vector Machines (SVM) algorithm.
   (Hint: SVM finds an optimal hyperplane to separate classes with the largest margin.)

3. Split the dataset into training and testing sets using a 75:25 ratio. Utilize the `train_test_split` function from scikit-learn.
   (Hint: Import `train_test_split` and provide the necessary arguments: dataset, test size, and random state.)

4. Train an SVM classifier on the training data. What is the chosen kernel for the SVM? Utilize the `SVC` class from scikit-learn.
   (Hint: Import `SVC` and create an instance. Use the `fit` method with the training data.)

5. Make predictions on the testing data using the trained SVM model.
  ( Hint: Use the `predict` method with the testing data.)

6. Calculate the accuracy, precision, and recall of the SVM model using appropriate functions from scikit-learn.
   (Hint: Import the necessary metrics and apply the respective functions using predicted labels and ground truth labels.)

7. How does SVM handle non-linearly separable data? Explain the concept of the kernel trick.
   (Hint: SVM can transform data into a higher-dimensional space using a kernel function.)

8. Use the `GridSearchCV` class from scikit-learn to perform hyperparameter tuning for the SVM model. Tune the C parameter and the choice of kernel. What are the best values found for these hyperparameters?
   (Hint: Import `GridSearchCV` and specify the parameter grid. Access the best parameters using the `best_params_` attribute.)

9. Visualize the decision boundary of the SVM model on a scatter plot of the test data points using Matplotlib.
   (Hint: Create a mesh grid of points, use the `predict` method on the mesh grid, and plot the mesh grid and scatter plot.)
