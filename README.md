# Unscented Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

In this project utilize an Unscented Kalman Filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower that the tolerance outlined in the project reburic. 

## Content in Repository
- scr directory with the project code:
  - main.cpp - calls for UKF filter file with feed data
  - ukf.cpp - initializes the filter variable, and the predict and update function based on radar and lidar data
  - tools.cpp - calculates the RSME error
  
## Test Result
Based on the dataset 1 result, the error graph is shown below:

![result.png](https://github.com/wenkairen/CarND-Extended-Kalman-Filter-Project/blob/master/CarND-Extended-Kalman-Filter-Project/result.png)

the output of the result satidfiy the RMSE <= [.09, .10, .40, .30]. requirement.
