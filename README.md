# Data-Wrangling-Exercise

This assignment aims to make use of R and R packages dplyr and plyr for a beginner user using a public dataset. 


About: 
The assigment has four main components: 1) Compile all test and train data sets into a large dataset; 2) extract columns containing standard deviation and mean; 3) add new variables containing activity labels and names; 4) create a separate data set showing the averages of each measurement by subject and activity.

Files:
The original data set can be found here: archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
This dataset contains information from a research experiment where 30 subjects practiced 6 different activities with a smartphone attached to them. 
There are 8 files within the data set for use in this assignment.
features.txt - Holds the variable names for X_test and X-train.
X_test.txt - Measurements of each activity completed by certain subjects in study test.
X_train.txt - Measurements of each activity completed by certain subjects in study training.
y_test.txt - Contains numeric activity data for X_test respectively.
y_train.txt - Contains numeric activity data for X_train respectively.
activity_labels.txt - Contains the codes for each activity name.
subject_train.txt - Contains subject data for X_train respectively.
subject_test.txt - Contains subject data for X_test respectively.

Run_anaysis.R is the script used for all preliminary data munging and the above four steps. 

