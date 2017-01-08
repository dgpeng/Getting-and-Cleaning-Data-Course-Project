Data source:
1, https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2, please unzip it and rename the unzipped folder as "UCI"
The Variables:
1, the train data, "x.train", "y.train" and "subject.train", which will be extracted from "/train/X_train.txt", "/train/y_train.txt", and "/train/subject_train.txt".
2, the test data, "x.test", "y.test" and "subject.test", which will be imported from "/test/X_test.txt", "/test/y_test.txt" and "/test/subject_test.txt". 
3, the activity labels are imported from "/activity_labels.txt" into "activity.labels"
4, the names of the measurements are imported from "/features.txt" into "features".
Data Analysis
1, load all the tables mentioned in the section of "variables" individually
2, bind data
3, merge test and train data
4, apply mean function to dataset
5, write table

Final data, "tidy_data.txt", will be saved in the parent folder of the folder "UCI".
