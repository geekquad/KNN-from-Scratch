# KNN-from-Scratch
KNN which stands for K-Nearest Neighbours is a simple algorithm that is used for **classification** and **regression** problems in Machine Learning. KNN is a **non-parametric** and **lazy learning algorithm**. Non-parametric means there is no assumption for underlying data distribution. In other words, the model structure determined from the dataset. This will be very helpful in practice where most of the real world datasets do not follow mathematical theoretical assumptions. Lazy algorithm means it does not need any training data points for model generation. All training data used in the testing phase. This makes training faster and testing phase slower and costlier. Costly testing phase means time and memory. 
<p> In the worst case, KNN needs more time to scan all data points and scanning all data points will require more memory for storing training data. </p>

### Working of KNN:
In KNN, K is the number of nearest neighbors. The number of neighbors is the core deciding factor. K is generally an odd number if the number of classes is 2. When K=1, then the algorithm is known as the nearest neighbor algorithm. This is the simplest case. 
<img src="https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1531424125/Knn_k1_z96jba.png">
<hr> </hr>

### Documentation of KNN:
<a href="https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html">https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html</a>
<hr> </hr>

### Parameters:
<ul>
  <li><b>n_neighbors (default value = 5)</b></li>
  n_neighbors represents the number of neighbors to use for kneighbors queries
  
  > The determination of the K value varies greatly depending on the case.
  
  <li><b> p: (default=”minkowski”)  </b></li>
  This is the power parameter for the Minkowski metric.
  
  > When p = 1, this is equivalent to using manhattan_distance (l1)
 <p> 
  
  > When p = 2, this is equivalent to using euliddean_distance(l2)</p>
  </ul>
