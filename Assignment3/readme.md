run_Analysis.R script performs the following steps to clean the data:
a.	Download the file and put the file in the data folder.
b.	Unzip the file
c.	Read data from the files into the variables:
i.	dataActivityTest reads data from file: y_test.txt
ii.	dataActivityTrain reads  data from file: y_train.txt
iii.	dataSubjectTrain reads data from file: subject_train.txt
iv.	dataSubjectTest reads data from file: subject_test.txt
v.	dataFeaturesTest reads data from file: X_test.txt
vi.	dataFeaturesTrain reads data from file: X_train.txt
d.  Merge the training and the test sets to create 3 data frames: dataSubject, dataActivity, dataFeatures.
e.  Merge columns to get the data frame 'Data' for all data frames -  dataSubject, dataActivity, dataFeatures.
f.  Extract only the measurements on the mean and standard deviation for each measurement from the data frame 'Data'.
g.  Read descriptive activity names from file ÎéÎíactivity_labels.txtÎéÎí into data frame: activityLabels
h.  Appropriately labels the data set with descriptive variable names.
i.  Creates a second,independent tidy data set and ouput it.  
		     
