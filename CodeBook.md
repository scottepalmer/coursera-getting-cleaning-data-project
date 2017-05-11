Description
Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.

My Script
The file "run_analysis.R" performs the 5 following steps:

1. Merging the training and the test sets to create one data set
  a) Reading files
    1.) Reading activity labels
    2.) Reading feature vector
    3.) Reading training tables
    4.) Reading testing tables
  b) Assigning column names
  c) Merging all data in one set
  
2. Extracting only the measurements on the mean and standard deviation for each measurement
  a) Reading column names
  b) Create vector for defining ID, mean and standard deviation
  
3. Using descriptive activity names to name the activities in the data set

4. Appropriately labeling the data set with descriptive variable names

5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject
  a) Making second tidy data set
  b) Writing second tidy data set in txt file