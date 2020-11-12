# Reccomendation-systems-Implementation
Implementing Content based filtering (similarity measures) ,  collaborative filtering(Matrix Factorisation) and Neural network based methods.

## Method 1 : Similarity Measures
### 1. Cosine similairty
  * Time taken : 3-5 seconds on imdb data of 14332 movies
  * Average rmse : 1.256
### 2. Modified Norm-Cosine similairty
 * Time taken : 3 minutes on imdb data of 14332 movies
  * Average rmse :  0.875

## Method 2 : Matrix-Factroization (MF)
 * Dataset : 100k ratings by 1000 users on 10000 movies (Sparse dataset) 
 * MF on toy data: RMSE = 0.0273
 * MF on a subset of 1k ratings(data points) : Time taken = 1 min & RMSE = 0.667
 * MF on a subset of 10k ratings(data points) : Time taken = 10-12 min & RMSE = 0.086
 * Note : If we use pandas pivot function data conversion is done within secs. But if we use naive methods then timetaken for data conversion {entire dataset} : 14-15 mins. 
 ### Error Plot (RMSE vs No.of Ratings) 
<img src="https://github.com/adarshX/Recommendation-systems-Implementation/blob/master/Matrix%20Factorization/RMSE_vs_datapoints.png" width="500" height="350" />


## Method 3 : Neural networks based recommender system
  * Dataset : 100k ratings by 1000 users on 10000 movies (Sparse dataset) 
  * NN on a subset of 1k ratings(data points) : Time taken = 1 min & RMSE = 0.453
  * MF on a subset of 10k ratings(data points) : Time taken = 8-10 min & RMSE = 0.027
  * Note : Keras functions have been used to increase the speed of the program.
  ### Error Plot (RMSE vs No.of datapoints)
  <img src = "https://github.com/adarshX/Recommendation-systems-Implementation/blob/master/Neural%20network%20Recommender%20system/NN_RMSE_vs_datapoints.png" width="500" height="350" />
   
   
