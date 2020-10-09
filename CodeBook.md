# Getting and Cleaning Data
## Course Project Code Book

## Processed data
Following the instrucions of the project the following variables were created and transformed:
* 'Set': Contains the merged data of 'X_train.txt' and 'X_test'.
* 'Subjects': Contains the merged data of 'subject_train.txt' and 'subject_test.txt'.
* 'Labels': Contains the merged data of 'y_train.txt' and 'y_test.txt'.
* 'AllFeatures': Contains all the features of 'features.txt'.
* 'IndexDesiredFeatures': Contains the indices of the desired features to process (measurements on the mean and standard deviation).
* 'SetDesiredFeatures': Contains the data only for the desired features.
* 'AllActivities': Contains the six performed activities.

In order to use more human-friendly names, the built-in funcion gsub() has been repeatedly used in order to make changes like for example:
* tBodyAcc-mean()-X --> tBodyAcc-mean-X

 or:
* tBodyAcc-mean()-X --> tBodyAccMeanX

## Appropriately labels the data set with descriptive variable names
* code column in TidyData renamed into activities
* All Acc in column’s name replaced by Accelerometer
* All Gyro in column’s name replaced by Gyroscope
* All BodyBody in column’s name replaced by Body
* All Mag in column’s name replaced by Magnitude
* All start with character f in column’s name replaced by Frequency
* All start with character t in column’s name replaced by Time

#### File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work)

* FinalData (180 rows, 88 columns) is created by sumarizing TidyData taking the means of each variable for each activity and each subject, after groupped by subject and activity.
* Export FinalData into TydeData.txt file.
