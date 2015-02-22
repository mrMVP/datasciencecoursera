# README for Course Project 2

## Analysis instructions:

1) Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say C:\Users\yourname\Documents\R\

2) Put run_analysis.R into C:\Users\yourname\Documents\R\UCI HAR Dataset\

3) In RStudio: setwd("C:\\Users\\yourname\\Documents\\R\\UCI HAR Dataset\\"), followed by: source("run_analysis.R")

4) Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.

**Detailed information regarding *run_analysis.R* you can find in CodeBook.md**
