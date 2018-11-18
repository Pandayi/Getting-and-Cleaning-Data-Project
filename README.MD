This repository contains the following files
CodeBook.md, the code book, which describes the contents of the data set (data, variables and transformations used to generate the data).
run_analysis.R, the R script that was used to create the data set
README.md, this file, which provides an overview of the data set and how it was created.
tidy_data.txt, which contains the data set.

The R script run_analysis.R can be used to create the data set. It retrieves the source data set and transforms it to produce the final data set by implementing the following steps
Download the dataset if it does not already exist in the working directory
Load the activity and feature info
Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidy.txt.
