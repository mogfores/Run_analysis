**Getting and Cleaning Data**

Project to create a *.R script called run_analysis.R, with the results:

1.Merges the training and the test sets to create one data set.

2.Extracts only the measurements on the mean and standard deviation for each measurement. 

3.Uses descriptive activity names to name the activities in the data set

4.Appropriately labels the data set with descriptive variable names. 

5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

**Steps for working on this course project**

Download the datasource and place it in the main folder of the RStudio directory on your local drive.
Unzip the folder. You will have a folder called UCI HAR Dataset.

Create an R file named run_analysis.R in the parent folder of the UCI HAR dataset, then set it as your working directory using the setwd() function in RStudio.
Run the source code ("run_analysis.R"), then it will generate a new tiny_data.txt file in your working directory.
