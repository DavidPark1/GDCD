#GDCD

Coursework - Getting and Cleaning Data Course Project - README.md

2016 May 15  Version 1.0 

>Source Data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
>Source Data description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
>Source Data description 2: http://archive.ics.uci.edu/ml/machine-learning-databases/00240/UCI%20HAR%20Dataset.names

###The dataset includes the following files (directly from Source Data description 2):
>=========================================
>- 'README.txt'
>- 'features_info.txt': Shows information about the variables used on the feature vector.
>- 'features.txt': List of all features.
>- 'activity_labels.txt': Links the class labels with their activity name.
>- 'train/X_train.txt': Training set.
>- 'train/y_train.txt': Training labels.
>- 'test/X_test.txt': Test set.
>- 'test/y_test.txt': Test labels.

>The following files are available for the train and test data. Their descriptions are equivalent. 
>- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 
>- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 
>- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 
>- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 


###Created Data/Files:
>1. README.md
>2. Codebook.md
>3. run_analysis.R

###The assignment is to create on R script, "run_analysis.R" that will:
>1. Merges the training and the test sets to create one data set.
>2. Extracts only the measurements on the mean and standard deviation for each measurement.
>3. Uses descriptive activity names to name the activities in the data set.
>4. Appropriately labels the data set with descriptive variable names.
>5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

###Instructions:
>1. Review "Source Data description" to familiarize with original data collection & classification.
>2. Download and unzip the file from "Source Data" into your working directory.
>3. Place "run_analysis.R" into your working directory and review Codebook.txt to review R script and details.
>4. Source "run_analysis.R" to result in an independant tidy data set, "tiny_data.txt" into your working directory.
