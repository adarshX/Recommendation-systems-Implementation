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
 ### Error Plot (RMSE vs No.of Ratings) 
<img src="https://github.com/adarshX/Recommendation-systems-Implementation/blob/master/Matrix%20Factorization/RMSE_vs_datapoints.png" width="500" height="250" />


## Method 3 : Neural networks based recommender system
  ### Accuracy Plot (accuracy vs No.of datapoints)
   <img src = "https://github.com/adarshX/Recommendation-systems-Implementation/blob/master/Neural%20network%20Recommender%20system/accuracy_vs_training_size.png" />
   
   ### Top 10 recommendations prediction Accuracy Plot (prediction accuracy vs No.of datapoints)
   <img src =https://github.com/adarshX/Recommendation-systems-Implementation/blob/master/Neural%20network%20Recommender%20system/top10_accuracy.png  width = "500"/>
