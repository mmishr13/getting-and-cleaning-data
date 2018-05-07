# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
In this project, data collected from the accelerometer and gyroscope of the Samsung Galaxy S smartphone was retrieved, worked with, and cleaned, to prepare a tidy data that can be used for later analysis.

This repository contains the following files:
1. README.md, this file, which provides an overview of the data set and how it was created.
2. tidy_data.txt, which contains the data set.
3. CodeBook.md, the code book, which describes the contents of the data set (data, variables and transformations used to generate the data).
4. run_analysis.R, the R script that was used to create the data set 

The R script run_analysis.R can be used to create the data set. 
It retrieves the source data set and transforms it to produce the final data set by implementing the following steps:

1. Download and unzip source data if it doesn't exist.
2. Read data.
3. Merge the training and the test sets to create one data set.
4. Extract only the measurements on the mean and standard deviation for each measurement.
5. Use descriptive activity names to name the activities in the data set.
6. Appropriately label the data set with descriptive variable names.
7. Create a second, independent tidy set with the average of each variable for each activity and each subject.
8. Write the data set to the tidy_data.txt file.

The tidy_data.txt in this repository was created by running the run_analysis.R script using R version 3.2.2 (2015-08-14) on Windows 8.1 64-bit edition.
This script requires the dplyr package (version 0.4.3 was used).
