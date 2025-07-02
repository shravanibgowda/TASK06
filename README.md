K-Nearest Neighbors (KNN) Classification on Iris Dataset
This project demonstrates a simple implementation of the K-Nearest Neighbors (KNN) classification algorithm using the famous Iris dataset. The task involves data preprocessing, model training, and evaluation using various values of k.

Dataset
The dataset used is the Iris flower dataset, which contains 150 samples with four features:

Sepal Length

Sepal Width

Petal Length

Petal Width
And a target variable indicating the flower class:

Iris-setosa

Iris-versicolor

Iris-virginica

Features
Data loading and preprocessing using pandas and scikit-learn

Feature scaling using StandardScaler

Model training using KNeighborsClassifier

Evaluation via accuracy and confusion matrix

Visualization of performance across different k-values

Libraries Used
pandas

numpy

matplotlib

seaborn

scikit-learn

How to Run
Clone this repository or download the notebook.

Make sure you have Python and required libraries installed.

Run the notebook (task6.ipynb) in Jupyter Notebook or any IDE that supports .ipynb files.

Output
Accuracy scores for different values of k (1–10)

Confusion matrix for the best-performing model
