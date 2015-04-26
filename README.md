# Run_Analysis_Repo
## Class Project for "Getting and Cleaning Data"

One of the most exciting areas in all of data science right now is wearable computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.


**Here are the steps that must be performed before running the R script:**

# General Outline for project
* 'You should create one R script called run_analysis.R that does the following.'
* 'Merges the training and the test sets to create one data set.'
* 'Extracts only the measurements on the mean and standard deviation for each measurement.' 
* 'Uses descriptive activity names to name the activities in the data set'
* 'Appropriately labels the data set with descriptive variable names.' 
* 'From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.'

# Steps followed
1. Download the zip file from [this URL](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).
2. Unzip the file.
3. Move ALL of the following files to the SAME DIRECTORY as the R script:
	* `features.txt`
	* `subject_train.txt`
	* `subject_test.txt`
	* `X_train.txt`
	* `X_test.txt`
	* `y_train.txt`
	* `y_test.txt`

**Once those steps are complete, you can run the R script ([run_analysis.R](run_analysis.R)).** Note that it requires the [reshape2 package](http://cran.r-project.org/web/packages/reshape2/index.html), which can be downloaded from CRAN.

**The output of the R script is a tidy data set, tidy_HCI_data.txt.**

You can read more about the data and the analysis in the [code book](CodeBook.md).
