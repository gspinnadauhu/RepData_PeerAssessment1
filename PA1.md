# Reproducible Research: Peer Assessment 1
gspinnada uhu  


## Loading and preprocessing the data
Unzipping & Loading data

```r
unzip("./activity.zip")
activity<-read.csv("./activity.csv")
```
Reclassing date as Date and steps as numeric

```r
activity$date<-as.Date(activity$date,"%Y-%m-%d")
activity$steps<-as.numeric(activity$steps)
```


## What is mean total number of steps taken per day?
1. Calculate the total number of steps taken per day
2. If you do not understand the difference between a histogram and a barplot, research the difference between them. Make a histogram of the total number of steps taken each day
3. Calculate and report the mean and median of the total number of steps taken per day



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
