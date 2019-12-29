# KNN

Knn uses the feature similarity to predict the new point that will fall on it.

1. K is the number identify the similar neighbor for the new data point
2. find the distance of new point of each data
3. find the k nearest neighbor to the new point 
4. new data point belong to the class which have more neighbors 

Distance calculation-

1. Eculidean distance
2. Manhatten distance
3. Hamming distance

code-
1. Load wine dataset from sklearn
2. Find Null values and replace it
3. StandardScaler()
4. Try elbow method to find the best K value for the model ( basically Brute force)
5. fit the model
6. calculate metrics

Basically, KNN is used to group the features based on feature similarity and fid the new point using neighborhood
