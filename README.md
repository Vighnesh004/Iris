K-Means Clustering on Iris Dataset
This project demonstrates the implementation of the K-Means clustering algorithm using the Iris dataset. The goal is to classify the data into clusters and visualize the results.

Prerequisites
Before running the code, ensure you have the following Python libraries installed:

numpy
matplotlib
pandas
scikit-learn
Install them using pip if necessary:

bash
Copy code
pip install numpy matplotlib pandas scikit-learn
Dataset
The project uses the Iris dataset, which is included in the repository. It contains data about three Iris flower species, with measurements for:

Sepal Length
Sepal Width
Petal Length
Petal Width
Code Description
Libraries Import: The code uses numpy, pandas, matplotlib, and sklearn for data manipulation, visualization, and clustering.

Data Loading: The Iris dataset is loaded using pandas.

Elbow Method: To determine the optimum number of clusters, the elbow method is applied by plotting the Within-Cluster Sum of Squares (WCSS) for clusters ranging from 1 to 10.

K-Means Clustering: The K-Means algorithm is applied with 3 clusters, as suggested by the elbow method.

Visualization: The clusters and their centroids are visualized using a scatter plot.
