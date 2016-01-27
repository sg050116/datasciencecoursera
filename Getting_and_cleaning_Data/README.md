# This is the courses project for Getting and cleaning data

Instruction for peer review:

1. Download and unzip your database to "data" from 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

or you can just download whole file in my repo

2. Make sure all files in the same directory. Then run following command in R:
$ source("run_analysis.R")

3. You will find 
merged_data.txt (7.9 Mb): it contains a data frame called cleanedData with 10299*68 dimension.
data_with_means.txt (220 Kb): it contains a data frame called result with 180*68 dimension.

4. Then run following command in R:
$ check <- read.table("data_with_means.txt")
$ check
you will found the 180 rows with all combinations for each of the 66 features.

## Thank you for your review
