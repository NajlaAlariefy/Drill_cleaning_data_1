# UCI-HAR-Project
Getting and Cleaning Data Course Project


## Files Contained: 

### CodeBook.md
To have a better understanding of the data, take a look at this file first.

### Run_Analysis.R
#### Description
This file will run all of the data summarization and tidying asked for in the project:

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement. 

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive variable names. 

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#### Running Process
To run it, make sure the "UCI HAR Dataset" folder is in your working directory. Also, make sure this file (Run_Analysis.R) is placed within "UCI HAR Dataset" folder.

### data_set_of_mean_values.txt
This text file contains the dataset of all of the averaged data. It has the dataset from STEP 5.
