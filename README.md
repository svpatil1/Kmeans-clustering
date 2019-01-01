# Kmeans-clustering-
Kmeans clustering  using Scikit dataset

Kmeans clustering is performed on Iris dataset of scikit library. The results are verified using pandas crosstab function.

| col  | 0 | 1 | 2 |
| ------------- | ------------- |------------- |------------- |
| row | | | |
| 0 |  50 | 0 | 0
| 1 | 0 | 48 | 2 |
| 2 | 0 | 14 | 36

###### Observation:

The above table shows that all the 50 data points with label 0 has been correctly predicted.
Whereas for label 1, 48 are correctly predicted and 2 are incorrectly predicted as label 2.
Also for label 2, 36 datapoints are correctly predicted and 14 datapoints are incorrectly predicted as label 1.


Now evaluating the result with Kmeans Classification report,

| | Precison | Recall| F-score | support |
| ------------- | ------------- | ------------- |------------- |------------- |
| 0 |  1.00 | 1.00 | 1.00 | 50 |
| 1 | 0.77 | 0.96 | 0.86 | 50 |
| 2 | 0.95 | 0.72 | 0.82 | 50 |
| avg/total | 0.83 | 0.83 | 0.83 | 150 |

High Precision + High Recall = Highly accurate model.

Thus, this model gives 83% of the data which are truly relevant.
