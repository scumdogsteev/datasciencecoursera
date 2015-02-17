# Getting and Cleaning Data Course Project
##### by Steve Myles, February 2015

### Assignment:
You should create one R script called run_analysis.R that does the following. 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Files:

1. README.md (this file)
2. run_analysis.R (the R script)
3. CodeBook.md (describes the variables, the data, and the work that is performed to clean up the data)

### Script (run_analysis.R)

#### Assumptions

1. The Samsung data is available in the working directory in an unzipped folder named "UCI HAR Dataset" with the directory structure underneath that left intact from the original zip file (e.g., there are subdirectories called "test" and "train" in "UCI HAR Dataset").
2. The user has either previously installed the [plyr](http://plyr.had.co.nz/) and [dplyr](http://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html) packages or is connected to the Internet so the script can install them.

#### Logic

Placeholder

### References

1. Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. [Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones). International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012.
2. David Hood.  [David's Course Project FAQ](https://class.coursera.org/getdata-011/forum/thread?thread_id=69).  Getting and Cleaning Data Discussion Forum.  Coursera.  Feb 2015.
3. Simon Hanlon. [Response to "Elegant way to check for missing packages and install them?"](http://stackoverflow.com/a/19870272). Stack Overflow. Nov 2013.
