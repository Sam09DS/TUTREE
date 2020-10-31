# Dimensionality reduction
## What is Dimensionality reduction?
**It is a technique used in ML to reduce the number of dimensions such that it retains only those most important components.**
* Dimensionality reduction, or dimension reduction, is the transformation of data from a high-dimensional space into a low-dimensional
  space so that the low-dimensional representation retains some meaningful properties of the original data, ideally close to its intrinsic
  dimension. Working in high-dimensional spaces can be undesirable for many reasons; raw data are often sparse as a consequence of the curse
  of dimensionality, and analyzing the data is usually computationally intractable. Dimensionality reduction is common in fields that deal
  with large numbers of observations and/or large numbers of variables, such as signal processing, speech recognition, neuroinformatics,
  and bioinformatics.Methods are commonly divided into linear and non-linear approaches.[1] Approaches can also be divided into feature
  selection and feature extraction.[2] Dimensionality reduction can be used for noise reduction, data visualization, cluster analysis,
  or as an intermediate step to facilitate other analyses.
  <img src = "https://github.com/Sam09DS/TUTREE/blob/main/Dimensionality%20reduction/1_4ibdHcy6xlV7-HU3KjonsQ.png" width="60%">
  <img src = "https://github.com/Sam09DS/TUTREE/blob/main/Dimensionality%20reduction/Dimensionality_Reduction_1.jpg" width="60%">
  
### Advantages:
1. Reduces computational complexity
2. Reduces overfitting
3. Helps in visualizing by reducing the number of high dimensions.

* Dimensionality reduction is used both in supervised and unsupervised learning techniques.

**PCA can be used for both supervised and unsupervised learning techniques**
**LDA can be used only for supervised learning technique**

* PCA:- Principal Component Analysis
  1. PCA preserves the correlation between features 
  2. The principal components in PCA are created by linear combination of original variables.(Calculated with concepts like eigen values)
  3. The principal components are orthogonal to each other.
  4. The first principal component represents the direction of maximum variance.
  5. PCA always performs well in a normalized dataset.
  
* LDA -- Linear Discriminant Analysis 
 1. LDA tries to reduce the dimensions of the feature set while retaining the information that discriminates the output class label as well.
 2. LDA tries to find a decision boundary around each cluster of a class 
 3. It will then project these data points in a new dimension such that all the clusters are separate from each other as much as possible. 
    hence, the individual points in a cluster are closer to the centroid of that particular cluster.
 4. These new dimensions form the linear discriminants of the feature set.
 
* Choose PCA --> When the data is highly irregular in terms of 
               distribution (skewed)
* Choose LDA --> Uniform distribution 

 
 
 
