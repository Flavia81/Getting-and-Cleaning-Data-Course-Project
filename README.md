# Getting-and-Cleaning-Data-Course-Project

This repository contains my work for the course project for the Coursera course "Getting and Cleaning data", part of the Data Science 
specialization. What follows first are my notes on the original data.

A few steps were taken to transform the initial data set. The test and train sets have were merged and the subject identifiers and 
activity labels were pulled in to create a single data set. The activity identifiers were translated from identifiers into readable names. 
Only the mean and standard deviation variables were kept. Those variables were further summarized by taking their mean for each 
subject/activity pair. 

The data is in "wide" format. 
There is a single row for each subject/activity pair, and a single column for each measurement.

The final data set can be found in the tidydata.txt file, which can be read into R with read.table("tidydata.txt", header = TRUE). 

The description of the variables can be found in CodeBook.md
