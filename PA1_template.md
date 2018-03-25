---
title: "Reproducible Research: Peer Assessment 1"
author: "Author: rrwiren"
date: "Current date: 25 March, 2018"
output: 
  html_document:
    keep_md: true
---

---
## Loading libraries and some housekeeping
---


## Loading and preprocessing the data


```r
if(!file.exists('activity.csv')){
    unzip('activity.zip')
}
activity <- read.csv('activity.csv')
```

---
### Having a look at the data
---





## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?




## Additional information
