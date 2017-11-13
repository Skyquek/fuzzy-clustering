# fuzzy-clustering

This work trys to determine best possible clustering on a dataset using FCM, by finding the optimal paramters (m, C)
'm' - Fuzzy exponent

'C' - No. of clusters 

'C' - [2, C_max] (C_max = sqrt(No. of samples))

'm' - [1.5, 2.5]

Various values will be tried using QBits
The Quantum rotational gate would help find the optimal value over generations, given a fitness function
Fitness function is based on a propsed validity index, which measures clustering quality

Clustering is measured by:
- Intra-cluster compactness
- Inter-cluster separation 
- overlap

Mathematical methods are devised to quantify and measure the three paramters. Thereby giving the fitness function.
Fitness functions qunatifies and helps compare clustering results to find optimal values
