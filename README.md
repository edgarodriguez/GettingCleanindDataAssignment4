# Getting and Cleaning Data Week 4 Assignment (Final assignment)

This repo was created for the final assignment of Getting and Cleaning Data course (Coursera).
* First, download and unzip the data file into your R working directory.
* Second, download the R source code into your R working directory.
* Finally, execute R source code to generate tidy data file.

### Data 
Files X (test and train) are sensor signals. 
Files Y (test and train) indicates activity type.

### Code
The code combined training dataset and test dataset,  and extracted partial variables (mean and STD) to create another dataset.

### New dataset
The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

### Packages used
*dplyr


### The code was written based on the instruction of this assignment


1. Merges the training and the test sets to create one data set.
Use command rbind to combine training and test set
2. Extracts only the measurements on the mean and standard deviation for each measurement.
Use grep command to get column indexes for variable name contains "mean()" or "std()"
3. Uses descriptive activity names to name the activities in the data set
Convert activity labels to characters and add a new column as factor
4. Appropriately labels the data set with descriptive variable names.
Give the selected descriptive names to variable columns
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

