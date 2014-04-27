### Raw data
The raw data is here https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

The process on cleaning and formating data with a briefly explanation (of why we use that functions) is in the analysis file as comments.

This codebook is for the tidy data

### Variables

There are 68 variables in the tidy data.
You can see it using names(result). Using sapply(result, class). "mean" means mean and "std" means standard deviation

Only activity variable is character (or factor) the next variables are numeric (except subject that it is integer)
