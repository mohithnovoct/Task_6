# Task_6

# K-Nearest Neighbors (KNN) Classification on Iris Dataset

This project implements the K-Nearest Neighbors (KNN) classification algorithm on the Iris dataset using Python and Scikit-learn. It includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

## Dataset

* **Source**: [Kaggle - Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
* **Description**: The dataset consists of 150 samples from three species of Iris flowers: Setosa, Versicolor, and Virginica. Each sample includes four features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width

## Objectives

* Implement KNN classifier.
* Normalize features.
* Experiment with different values of K.
* Evaluate performance using accuracy and confusion matrix.
* Visualize decision boundaries using PCA.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Steps Performed

1. **Data Loading**

   * Read the Iris dataset CSV file.
2. **Preprocessing**

   * Dropped the `Id` column.
   * Encoded categorical labels.
   * Normalized feature values using `StandardScaler`.
3. **Model Training**

   * Split data into training and testing sets (80/20).
   * Trained `KNeighborsClassifier` for K values from 1 to 10.
4. **Evaluation**

   * Computed accuracy for each K.
   * Chose the best K based on maximum accuracy.
   * Generated confusion matrix and classification report.
5. **Visualization**

   * Plotted accuracy vs. K.
   * Applied PCA for dimensionality reduction.
   * Plotted decision boundaries for visualization.

## Results

* Achieved high accuracy (\~96%) with optimal K value.
* KNN classifier successfully distinguished between the three Iris classes.

## Visuals

* Accuracy vs. K Plot
* Confusion Matrix Heatmap
* 2D Decision Boundary using PCA
