# KNN-Image-compression
For this project, we'll be using a non-parametric classification method, k-nearest neighbors algorithm, to compress images.

We will first assign how many clusters we want, ranging from 2,4,8 & 16 clusters. We will then assess each data points distance 
to each cluster via the l2 norm, and assign that data point the closest clusters RGB set. The centroids will then be re-adjusted.

This process will repeat until centroid locations converge. The dataset will then be re-shaped to display the compressed image.
