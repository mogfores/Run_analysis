***CodeBook***

This is a codebook that describes the variables, data, and any other transformations you've performed to clean up the data.

**The data source**

Link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

**Dataset Information**

The experiments were tested with a group of 30 people with an age range of 19 to 48 years. Each person performed six activities, namely: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LEAVING, using a Samsung smartphone, Galaxy S II model on their waist. Using its built-in accelerometer and gyroscope, we capture 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. Tests were videotaped to manually label data. The data set obtained was randomly partitioned into two sets, where 70% of the volunteers were selected to generate the training data and 30% the test data.
Sensor signals were pre-processed by applying noise filters and then posted in fixed-width sliding windows of 2.56 seconds and 50% overlap.
The acceleration signal sensor, which has both gravitational and body motion components, was separated using a Butterworth low-pass filter for body acceleration and gravity. The gravitational force is considered to have only low frequency components, therefore a filter with a cut-off frequency of 0.3 Hz was used. From each window, a feature vector was obtained by calculating time and frequency domain variables.

**The data**

The dataset includes the following files:
'README.txt'
'features_info.txt': Shows information about the variables used on the feature vector.
'features.txt': List of all features.
'activity_labels.txt': Links the class labels with their activity name.
'train/X_train.txt': Training set.
'train/y_train.txt': Training labels.
'test/X_test.txt': Test set.
'test/y_test.txt': Test labels.

