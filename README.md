# Cleaning Data Course Project

* This is the course project for the Getting and Cleaning Data Coursera course.

A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

### Review criteria

1. The submitted data set is tidy.
2. The Github repo contains the required scripts.
3. GitHub contains a code book that modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information.
4. The README that explains the analysis files is clear and understandable.
5. The work submitted for this project is the work of the student who submitted it.

The following files from the initial dataset is used:

1. features.txt - includes the descriptions for features measured
2. X_train.txt - includes the measurements of the features in train set (one row - 1 measurement of 561 features)
3. X_test.txt - includes the measurements of the features in test set
4. subject_train.txt - subject for each measurement from the train set
5. subject_test.txt - subject for each measurement from the test set
6. y_train.txt - activity (from 1 to 6) for each measurement from the train set
7. y_test.txt - activity (from 1 to 6) for each measurement from the test set

![alt text](https://camo.githubusercontent.com/5fd927fe010efd2071020bc17bd2b82b8320c6c3/687474703a2f2f692e696d6775722e636f6d2f477930396e30492e706e67 "Logo Title Text 1")

#### The R script run_analysis.R has been created following the project instructions:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

