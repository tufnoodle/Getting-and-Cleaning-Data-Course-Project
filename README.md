# Getting & Cleaning Data Course Project

The current course deliverable is comprised of the following:  
  * README.md............(this file)  
  * CodeBook.md..........Describes the each value in the data set
  * run_analysis.R.........Script takes the raw data and converts to tidy per the instructions below  
  
## Summary  
The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The tasking is to prepare tidy data that can be used for later analysis. Submission requirement is to write an R script that executes the following:  

1. Merges the training and the test sets to create one data set.  
2. Extracts only the measurements on the mean and standard deviation for each measurement.  
3. Uses descriptive activity names to name the activities in the data set.  
4. Appropriately labels the data set with descriptive variable names.  
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.  

The data set is comprised of data collected from Samsung Galaxy S smartphone accelerometers. The data can be downloaded from here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

A full description of the data set can be found here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

### Important Note  
The script must reside in the same directory as the 'activity_labels.txt' file from the downloaded data
