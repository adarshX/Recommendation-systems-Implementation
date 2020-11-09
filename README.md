# Reccomendation-systems-Implementation
Implementing Content based filtering and collaborative filtering(Matrix Factorisation) methods

## Method 1 : Similarity Measures
### 1. Cosine similairty
  * Time taken : 3-5 seconds on imdb data of 14332 movies
  * Accuracy acheived :  
### 2. Modified Norm-Cosine similairty
 * Time taken : 3 minutes on imdb data of 14332 movies
  * Accuracy acheived :  

## Method 2 : Matrix-Factroization (MF)
 * Dataset : 100k ratings by 1000 users on 10000 movies (Sparse dataset) 
 * MF on toy data: RMSE = 0.0273
 * MF on a subset of 1k ratings(data points) : Time taken = 1 min & RMSE = 0.267
 * MF on a subset of 10k ratings(data points) : Time taken = 10-12 min & RMSE = 0.016
 * Note : If we use pandas pivot function data conversion is done within secs. But if we use naive methods then timetaken for data conversion {entire dataset} : 14-15 mins. 
 ### Erro Plot (RMSE vs No.of Ratings) 
![Image of Yaktocat](https://github.com/adarshX/Recommendation-systems-Implementation/blob/master/Matrix%20Factorization/RMSE_vs_datapoints.png)
