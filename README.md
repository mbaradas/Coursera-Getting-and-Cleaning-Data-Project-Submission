# Coursera-Getting-and-Cleaning-Data-Project-Submission

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

R script run_analysis.R does the following:
1. Downloads the dataset if it does not already exist in the working directory.
2. Merges the training and the test sets to create one data set.
3. Extracts only the measurements on the mean and standard deviation for each measurement.
4. Uses descriptive activity names to name the activities in the data set.
5. Appropriately labels the data set with descriptive variable names.
6. The resulting out is in the file tidy.txt.
