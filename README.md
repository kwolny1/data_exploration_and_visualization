# Data Exploration and Visualisation
Project for university subject Data Exploration and Visualisation in the first semester of Master's Degree. 

In **2025L-DEV-project-assignment.pdf** there is a description of two exercises that were given to conduct for the project. 

I've included the presentation with results in **DEV_presentation.pdf**. 

## First Exercise
In the first exercise, a synthetic dataset was created for binary classification. Few columns were informative - they provided useful information about the 0-1 label. To the dataset were added noise data. 
Next, there is a comparison of three feature selection methods. Selected methods:  

- RFE - Recursive Feature Elimination used with SVM,
- CS - Correlation-based Selection,
- DTC - Decision Tree Classifier-based Selection.

For the evaluation of these 3 methods, I've used accuracy, precision, recall and F1 score on SVM and Random Forest models on :

- Set with all features
- Sets with features selected by chosen feature selection methods
- Set of only important features
- Data projection obtained via: 
  - PCA,
  - Multidimensional scaling,
  - TSNE.

The process was repeated 6 times in order to get an average behaviour. 

## Second Exercise

In the 2nd exercise, I've done clustering of 16 datasets and analysed them. I compared 4 different clustering methods with different algorithm parameters. 

- K-means
- Genie (with parameter g ∈ {0.1, 0.3, 0.5, 0.7, 0.9})
- Agglomerative Hierarchical Clustering (with single, average, complete and Ward linkage)
- DBSCAN
