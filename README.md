# Coursera---Getting-and-Cleaning-Data-Assignment
Getting and Cleaning Data - Coursera - R

# Intro
This repository contains the work completed for the "Getting and Cleaning Data" course that is part of the JHU Data Science Specialization.

# About the Raw Data
To start, the features were not labeled and were available in x_test.txt. Activity labels were found in the y_test.txt file. Test subjects are in the subject_test.txt file.

# About the script/tidy dataset
As per the instructions, I created a script called run_analysis.R which will merge the test and training sets together. Prereqs for this script is as followed:
1. It is imperative that the UCI HAR Dataset is extracted
2. UCI HAR Dataset is available in a dir called "UCI HAR Dataset"

After merging, testing and training - labels were added and only columns that have to do with the std and mean were retained.

To close, the script will create a tidy dataset containing the means of all the columns as per test subject and as per activity. This dataset was written to a file called tidy.txt - This file will also be in this repository.

# Code Book
Codebook.md file will explain the exercises performed and the results of the data and variables.
