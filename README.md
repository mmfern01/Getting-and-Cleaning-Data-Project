# Getting-and-Cleaning-Data-Project
This is a repository for code written for the Getting and Cleaning Data course project.

The code should accomplish the following: 

    Merges the training and the test sets to create one data set.
    Extracts only the measurements on the mean and standard deviation for each measurement. 
    Uses descriptive activity names to name the activities in the data set
    Appropriately labels the data set with descriptive variable names. 
    Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

In order to employ the script:

Unzip data (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on a local drive.

Download run_analysis.R into the same folder.

Change the working directory to the aforementioned folder.

Use read.table("data_averages.txt") to read the data. 
