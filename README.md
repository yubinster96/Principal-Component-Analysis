# Principal-Component-Analysis
PCA on breast cancer data from sklearn.datasets

Principal component analysis (PCA) is a dimensionality reduction and machine learning method used to simplify a large data set into a smaller set while still maintaining significant patterns and trends.

Steps:
Standardize the range of continuous initial variables
Compute the covariance matrix to identify correlations
Compute the eigenvectors and eigenvalues of the covariance matrix to identify the principal components
Create a feature vector to decide which principal components to keep
Recast the data along the principal components axes

from sklearn.decomposition import PCA

just from the first 2 PCA we went from 30 features to 2..

we use a heatmap at the end to actually visualize the correlation between the principal component with all the actual features..
