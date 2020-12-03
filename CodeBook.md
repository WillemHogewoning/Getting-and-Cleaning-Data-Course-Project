The run_analysis.R script works as follows:

Download the dataset
Dataset downloaded and extracted the datasets

Assign each data to variables


features <- "UCI HAR Dataset/features.txt"

activities <- "UCI HAR Dataset/activity_labels.txt"

subject_test <- "UCI HAR Dataset/test/subject_test.txt"

x_test <- UCI HAR Dataset/test/X_test.txt"

y_test <- "UCI HAR Dataset/test/y_test.txt"

subject_train "UCI HAR Dataset/train/subject_train.txt"

x_train <- "UCI HAR Dataset/train/X_train.txt"

y_train <- "UCI HAR Dataset/train/y_train.txt"


Then it merges the training and test set into one data set

Only the measurements on the mean and standard deviation for each measurement are extracted.

The decriptive names are re-used. 

code column in TidyData renamed into activities
All Acc in column’s name replaced by Accelerometer
All Gyro in column’s name replaced by Gyroscope
All BodyBody in column’s name replaced by Body
All Mag in column’s name replaced by Magnitude
All start with character f in column’s name replaced by Frequency
All start with character t in column’s name replaced by Time

An independent tidy data set is created with an avearge of each variable for each actitivity and subject.

