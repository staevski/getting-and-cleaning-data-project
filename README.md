# Getting and Cleaning Data Course Project

The R file run_analysis.R does the following:

1. Download the dataset if it does not already exist in the working directory
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
4. Loads the activity and persons data for each dataset, and merges those
   columns with the dataset
5. Merges the two datasets
6. Converts the activity and test persons columns into factors
7. Creates a tidy dataset that consists of the mean value of each
   variable for each subject and activity pair.

The result (the tidy data) is stored in the file tidy.txt.
