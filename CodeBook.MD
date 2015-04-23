## Getting and Cleaning Data Project

### 1. Merge the training and the test sets to create one data set.
After setting the source directory for the files, read into tables the data located in
- features.txt
- activity_labels.txt
- subject_train.txt
- x_train.txt
- y_train.txt
- subject_test.txt
- x_test.txt
- y_test.txt

Assign column names and merge to create one data set.

### 2. Extract only the measurements on the mean and standard deviation for each measurement. 
Create a vector that contains TRUE for the ID, mean and stdev columns and FALSE  for the others entities. Subset to get all necessary columns data to keep only the necessary columns.

### 3. Use descriptive activity names to name the activities in the data set
Merge data subset with the activityType table to include the descriptive activity names

### 4. Appropriately label the data set with descriptive activity names.
Use gsub for pattern recognition and replacement and clean up data labels

### 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
Produce only a data set with the average of each variable for each activity and subject