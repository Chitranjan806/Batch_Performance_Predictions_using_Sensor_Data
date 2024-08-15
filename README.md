# Batch Performance Predictions using Sensor Data
## Problem Statement
Using the given data of input parameters that are the 55 sensors of machines performing in batches at every time period i.e recorded at 7 instances we will find the statistical dependency. 
As this is a Regression problem to predict whether the machines are performing the best we have followed certain regression algorithms.

### Modelling
R2_Scores of every model for shuffled data, we obtained.

<b>Using XGBRegressor >> 0.48<br>
Using KNeighborsRegressor >> 0.42<br>
Using RandomForestRegressor >> 0.38<br>
Using GradientBoostingRegressor >> 0.36<br>
Using Linear Regression >> 0.17</b><br>

### The predictions as per XGBRegressor
<img src="predictions_graph.png" width=500 height=350 />

### Results 
**The predictions with the test data were exported in a csv file, which was used by the submission portal to generate R2 scores**

<hr>

### Outcomes
* <b>Operational Efficiency:</b>
By identifying performance trends over time, the model helps optimize machine operations, reducing downtime and improving overall efficiency. This leads to cost savings and increased production output.

* <b>Anomaly Detection:</b>
The model could be used to flag potential issues when predictions fall outside expected ranges, indicating machines that may require attention.
