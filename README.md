cleandatacoursera
=================

<h3>Overview</h3>
This repository contains an R script (r_analysis) which creates a tidy data set from the UCI HAR raw data set.  As an overview, it combines the training and test data, merges it with the subject and activity field, provides readable headers and activity names, and extracts only the means and standard deviations.  The UCI HAR data set was downloaded from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip on Aug 15, 2014.

<h3>Running the script</h3>
The script requires you have unzipped the UCI HAR data into your working directory with all the files and folder structure in tact.  Once you have done this, simply load the script into your R workspace of choice.  The command mergedTable <- run_analysis() will provide you with the tidy data set.

<h3>Merging the data sets</h3>
There are two folders within the raw data; a training and testing set.  This script combines both of these raw datasets into a single one after it has extracted the required information and added the necessary information as below.

<h3>Extracting the means and standard deviations</h3>
The requirements state that only the means and standard deviations should be in the file merged data set.  There is room for interpretation here, but I chose to include everything that had “mean” or “std” listed in the header as spelled out in the features.info file.  Please refer to the codebook for a complete list of included variables.

<h3>Adding Subject and Activities</h3>
In the raw data, the subjects and activities were in separate files.  This information was added to its corresponding row in the resulting table along with the header Subject and Activity.

<h3>Descriptive Activity Names</h3>
The activity name codes were replaced with readable real words (Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying).

<h3>Labeling with descriptive variable names</h3>
The original column names provided in the raw data contained various special characters and were not very readable.  The headers were processed as follows: <br>
•	All empty () were removed <br>
•	All () with enclosed text were replaced by a _ for the first ( and the trailing parentheses was eliminated <br>
•	All commas and dashes were replaced with underscores <br>
The result are headers that look like this example: fBodyGyro_mean_X.<br>
These are human readable, do not lose information, and should be process-able by a large variety of operating systems and programs.

<h3>Note on program layout</h3>
I used a second function to avoid duplicate code which takes file names as parameters.  In theory this would allow further data sets to be added if there were ever a need.  This also chose to clean each table separately and combine them at the end.
