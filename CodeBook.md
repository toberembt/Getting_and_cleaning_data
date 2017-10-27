## data used
Human Activity Recognition Using Smartphones Data Set. A full description is available at the site:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

## R script
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):   
1. Merging the training and the test sets to create one data set.      
2. Extracting only the measurements on the mean and standard deviation for each measurement    
3. Using descriptive activity names to name the activities in the data set   
4. Appropriately labeling the data set with descriptive variable names   
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject   

## variables:   
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `mrg_train`, `mrg_test` and `mrg_one` merge the previous datasets.
 
