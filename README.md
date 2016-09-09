# Getting-and-Cleaning-Data
 Project

This is the peer reviewed project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Downloads the dataset labelled "getdata_dataset.zip" if it does not already exist in the working directory
2. Unzips the data into folder labelled "UCI HAR Dataset" if it does not already exist in the working directory
3. Loads the activity and feature info
4. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
5. Loads the activity and subject data for each dataset, and merges those columns with the dataset
6. Merges the two test and train datasets
7. Appropriately labels the data set with descriptive variable names.
8. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file `tidydata.txt`.