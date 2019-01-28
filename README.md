# Getting-and-Cleaning-Data-Week-4-Assignment
This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.
First, download and unzip the data file into your R working directory. Second, download the R source code into your R working directory. Finally, execute R source code to generate tidy data file.

Data Description The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects. The variable in the data Y indicates activity type the subjects performed during recording.

Code Explanation The code combined training dataset and test dataset, and extracted partial variables to create another dataset with the averages of each variable for each activity.

New Dataset The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects

The code was written based on the instruction of this assignment -Read training and test dataset into R environment. -Read variable names into R envrionment. -Read subject index into R environment.

Merges the training and the test sets to create one data set. Use command rbind to combine training and test set
