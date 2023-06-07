# Grid Search Hyperparameter Optimization

This repository contains a case study on using grid searches to identify the optimal parameters for a machine learning algorithm. The case study focuses on the Pima Indian diabetes dataset from Kaggle and the KNN algorithm. The steps for preprocessing the data are outlined below.
1. Load the necessary packages.
2. Load the diabetes data.
3. Review the data information.
4. Apply the describe function to the data.
5. Replace the zero values in specific columns with NaN.
6. Plot histograms of each column.
7. Replace the NaN values with mean and median values.
8. Plot histograms of each column after replacing NaN.
9. Plot the correlation matrix heatmap.
10. Define the target variable and the feature variables.
11. Create a 70/30 train and test split.
12. Standardize the features using a scaler.
13. Apply the KNearestNeighbor classifier with a range of neighbor values.
14. Identify the number of neighbors that resulted in the maximum score in the training dataset and the testing dataset.
