Code book
This is the code book for tidy data set

Variables Description
Data read from project data files. For description of each data files, refer to README in the project folder.

listoffeatures - features.txt file

activity - activity_labels.txt file

subjecttests - subject_test.txt file

testX - X_test.txt

testY - Y_test.txt

subjectOftrain - subject_train.txt

trainX - train/X_train.txt

trainY -train/Y_train.txt

Processing variables
testY_label - match y_test labels with corresponding activities

t_test - binding test subject, test activity and test set

trainY_label - match y_train labels with corresponding activities

t_train - binding train subject, train activity and train set

t_set - merged test set and train set

t_mean_std - data set with only measurements on the mean and standard deviation for each measurement

t_avg - independent tidy data set with the average of each variable for each activity and each subject.
