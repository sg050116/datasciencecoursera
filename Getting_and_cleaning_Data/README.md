Getting and Cleaning Data Course Project
========================================

Project of [Getting and Cleaning Data course on Coursera](https://www.coursera.org/course/getdata), May 2014 edition.

## Project Description
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set.
The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers
on a series of yes/no questions related to the project.

You will be required to submit:

1. a tidy data set as described below
2. a link to a Github repository with your script for performing the analysis, and
3. a code book that describes the variables, the data, and any transformations or
   work that you performed to clean up the data called CodeBook.md. You should also
   include a README.md in the repo with your scripts. This file explains how all
   of the scripts work and how they are connected. 

One of the most exciting areas in all of data science right now is wearable computing.
Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced
algorithms to attract new users. The data linked to from the course website represent
data collected from the accelerometers from the Samsung Galaxy S smartphone.
A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following.

* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement. 
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive activity names. 
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

## What you find in this repository

* __CodeBook.md__: information about raw and tidy data set and elaboration made to
  transform them
* __LICENSE__: license terms for text and code
* __README.md__: this file
* __run_analysis.R__: R script to transform raw data set in a tidy one

#Instruction for peer review:

## How to create the tidy data set

1. clone this repository: `git clone git@github.com:sg050116/datasciencecoursera.git`
2. download [compressed raw data](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
3. unzip raw data and copy the directory `UCI HAR Dataset` to the cloned repository root directory & rename the `UCI HAR Dataset` into `data`
4. you will find
- merged_data.txt (7.9 Mb): it contains a data frame called cleanedData with 10299*68 dimension.
- data_with_means.txt (220 Kb): it contains a data frame called result with 180*68 dimensio
5. open a R console and set the working directory to the repository root (use setwd())
6. source run_analisys.R script : `source('run_analysis.R')`


In the repository root directory you find the file `data_with_means` with the tidy data set.# This is the courses project for Getting and cleaning data
7. check the result: `read.table("data_with_means.txt")`
you will found the 180 rows with all combinations for each of the 66 features.<br>

## Thank you for your review
