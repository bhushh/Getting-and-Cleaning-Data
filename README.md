# Getting-and-Cleaning-Data
This Repository was made as a part of the Coursera Peer-graded assignment for the course "Getting and Cleaning Data".

Steps for downloading the data:-
1. Download and unzip the data file into your R working directory.
2. Download the R source code into your R working directory.
3.  Execute R source code to generate tidy data file.

The R script (run_analysis.R) does the following:
1. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
2. Loads the activity and subject data for each dataset, and merges those columns with the dataset
3. Merges the two datasets
4. Converts the activity and subject columns into factors
5. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
6. The end result is shown in the file FinalData.txt.
