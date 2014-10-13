# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data


```r
myPA_data <- read.csv("activity.csv")
```

Here is some data:


```r
head(myPA_data)
```

```
##   steps       date interval
## 1    NA 2012-10-01        0
## 2    NA 2012-10-01        5
## 3    NA 2012-10-01       10
## 4    NA 2012-10-01       15
## 5    NA 2012-10-01       20
## 6    NA 2012-10-01       25
```

```r
tail(myPA_data)
```

```
##       steps       date interval
## 17563    NA 2012-11-30     2330
## 17564    NA 2012-11-30     2335
## 17565    NA 2012-11-30     2340
## 17566    NA 2012-11-30     2345
## 17567    NA 2012-11-30     2350
## 17568    NA 2012-11-30     2355
```

You can also embed plots, for example:


```r
pairs(myPA_data)
```

![plot of chunk unnamed-chunk-3](./PA1_My_2nd_attempt_files/figure-html/unnamed-chunk-3.png) 
\
## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
