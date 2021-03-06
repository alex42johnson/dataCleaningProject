This dataset contains records for 30 subjects. Using built-in tools of a smartphone (Samsung Galaxy S II), they were monitored across 6 different activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING).

The original dataset and more details on the methodology can be found at this website: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


A number of metrics were recorded (561 in total). The file final_summarized_results.txt  contains the following: 
* The mean of all variables  *x* from the original dataset, where all *x* variables are means or standard deviations of some other variable. The variables being averaged are as follows:

"tBodyAcc__mean__X"
"tBodyAcc__mean__Y"
"tBodyAcc__mean__Z"
"tBodyAcc__std__X"
"tBodyAcc__std__Y"
"tBodyAcc__std__Z"
"tGravityAcc__mean__X"
"tGravityAcc__mean__Y"
"tGravityAcc__mean__Z"
"tGravityAcc__std__X"
"tGravityAcc__std__Y"
 "tGravityAcc__std__Z"
"tBodyAccJerk__mean__X"
"tBodyAccJerk__mean__Y"
"tBodyAccJerk__mean__Z"
"tBodyAccJerk__std__X"
"tBodyAccJerk__std__Y"
"tBodyAccJerk__std__Z"
"tBodyGyro__mean__X"
"tBodyGyro__mean__Y"
"tBodyGyro__mean__Z"
"tBodyGyro__std__X"
"tBodyGyro__std__Y"
"tBodyGyro__std__Z"
"tBodyGyroJerk__mean__X"
"tBodyGyroJerk__mean__Y"
"tBodyGyroJerk__mean__Z"
"tBodyGyroJerk__std__X"
"tBodyGyroJerk__std__Y"
"tBodyGyroJerk__std__Z"
"tBodyAccMag__mean"
"tBodyAccMag__std"
"tGravityAccMag__mean"
"tGravityAccMag__std"
"tBodyAccJerkMag__mean"
"tBodyAccJerkMag__std"
"tBodyGyroMag__mean"
"tBodyGyroMag__std"
"tBodyGyroJerkMag__mean"
"tBodyGyroJerkMag__std"
"fBodyAcc__mean__X"
"fBodyAcc__mean__Y"
"fBodyAcc__mean__Z"
"fBodyAcc__std__X"
"fBodyAcc__std__Y"
"fBodyAcc__std__Z"
"fBodyAcc__meanFreq__X"
"fBodyAcc__meanFreq__Y"
"fBodyAcc__meanFreq__Z"
"fBodyAccJerk__mean__X"
"fBodyAccJerk__mean__Y"
"fBodyAccJerk__mean__Z"
"fBodyAccJerk__std__X"
"fBodyAccJerk__std__Y"
"fBodyAccJerk__std__Z"
"fBodyAccJerk__meanFreq__X"
"fBodyAccJerk__meanFreq__Y"
"fBodyAccJerk__meanFreq__Z"
"fBodyGyro__mean__X"
"fBodyGyro__mean__Y"
"fBodyGyro__mean__Z"
"fBodyGyro__std__X"
"fBodyGyro__std__Y"
"fBodyGyro__std__Z"
"fBodyGyro__meanFreq__X"
"fBodyGyro__meanFreq__Y"
"fBodyGyro__meanFreq__Z"
"fBodyAccMag__mean"
"fBodyAccMag__std"
"fBodyAccMag__meanFreq"
"fBodyBodyAccJerkMag__mean"
"fBodyBodyAccJerkMag__std"
"fBodyBodyAccJerkMag__meanFreq"
"fBodyBodyGyroMag__mean"
"fBodyBodyGyroMag__std"
"fBodyBodyGyroMag__meanFreq"
"fBodyBodyGyroJerkMag__mean"
"fBodyBodyGyroJerkMag__std"
"fBodyBodyGyroJerkMag__meanFreq"
"angle(tBodyAccMean_gravity)"
"angle(tBodyAccJerkMean)_gravityMean)"
"angle(tBodyGyroMean_gravityMean)"
"angle(tBodyGyroJerkMean_gravityMean)"
"angle(X_gravityMean)"
"angle(Y_gravityMean)"
"angle(Z_gravityMean)"


These means are grouped by subject and activity. So: for every activity that the subject performed, there will be averages across all 86 variables.