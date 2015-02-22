This file describes the variables, data and transformations performed for assignment 3. 
Data for the project is btained from:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
The run_analysis.R script performs the following steps to clean the data:
Download the file and put the file in the data folder.
Unzip the file
Read data from the files into the variables:
dataActivityTest reads data from file: y_test.txt
dataActivityTrain reads  data from file: y_train.txt
dataSubjectTrain reads data from file: subject_train.txt
dataSubjectTest reads data from file: subject_test.txt
dataFeaturesTest reads data from file: X_test.txt
dataFeaturesTrain reads data from file: X_train.txt
    d.  Merge the training and the test sets to create 3 data frames: dataSubject, dataActivity, dataFeatures.
    e.  Merge columns to get the data frame 'Data' for all data frames -  dataSubject, dataActivity, dataFeatures.
    f.  Extract only the measurements on the mean and standard deviation for each measurement from the data frame 'Data'.
   g.  Read descriptive activity names from file “activity_labels.txt” into data frame: activityLabels
   h.  Appropriately labels the data set with descriptive variable names.
   i.  Creates a second,independent tidy data set and ouput it.  
