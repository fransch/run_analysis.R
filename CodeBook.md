CodeBook.md

This is what the R script attached does to the data set uploaded according to the requirements of the course:

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.
  After creating a logical vector FALSE values were applied to all but ID, mean measurements and SD for each measurement

3. Uses descriptive activity names to name the activities in the data set
  The descriptive activity names were included by merging the subset created before with the activity type set

4. Appropriately labels the data set with descriptive variable names.
  gsub function was used 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
    The tidy data is names avarages_data2.txt 
