Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.

Source Data

A full description of the data used in this project can be found at The UCI Machine Learning Repository

The source data for this project can be found here.

Data Set Information

The project is about collecting 6 activities data from 30 volunteers and perform data analysis on the data about from gyroscope & accelerometer from smartphone. The 6 activies of WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING were performed by all volunteers. The data id divided into 30% test dataset and 70% train data set.

Attribute Information

For each record in the dataset it is provided:
.	Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
.	Triaxial Angular velocity from the gyroscope.
.	A 561-feature vector with time and frequency domain variables.
.	Its activity label.
.	An identifier of the subject who carried out the experiment.

Section 1. Merge the training and the test sets to create one data set.

Read the following tables for the data.

.	features.txt
.	activity_labels.txt
.	subject_train.txt
.	x_train.txt
.	y_train.txt
.	subject_test.txt
.	x_test.txt
.	y_test.txt

Assign column names and merge to create one data set.

Section 2. Extract only the measurements on the mean and standard deviation for each measurement.

A Logcal vector is created containing TRUE values for the ID, mean and stdev columns and consequently subset this data.

Section 3. Use descriptive activity names to name the activities in the data set

Merge data and give descriptive column names.

Section 4. Appropriately label the data set with descriptive activity names.

Use gsub function to clean up labels.

Section 5. Create a second, independent tidy data set with the average of each variable for each activity and each subject.

AS per the the project tasks , produce each variable average for each activity and subject

