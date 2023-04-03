# k-Means Clustering 
This folder contains the implementation of the k-Means Clustering Model.

## Description
In this notebook, I implemented k-Means clustering on the Shill Bidding dataset. Before apply the KMeans clustering on the data, I fitted the normalized data using PCA. Following the rule of thumb of keeping about 90% of the variance, I decided to keep the first 2 components. Afterward, I fitted K-Means clustering with different numbers of components, plot the inertia of the model versus the number of components on a graph, and by Elbow's method, find 2 as a reasonable k value.Finally, a k-Means clustering model with k = 2 was conducted. 

## Reference
Most of the contents in file are based on Dr. Davila's Lecture Notes and our text book 'Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow'.