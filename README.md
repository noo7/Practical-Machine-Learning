# Predicting the Quantified Self
Bastiaan Quast  
Monday, July 21, 2014  

## Abstract
A two line summary


## Introduction
quantified self, etc.


## Data
The data is taken from [Human Activity Recognition](http://groupware.les.inf.puc-rio.br/har)

We download the data and save it to local csv files. We specify the urls and destination files.

```r
training.url  <- 'https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv'
test.url      <- 'https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv'
training.file <- 'training.csv'
test.file     <- 'test.csv'
```
Then we run the download commands.

```r
download.file(training.url, training.file, method='wget')
download.file(test.url,     test.file, method='wget')
```
Next, we load the data from the csv files into the workspace.

```r
training <- read.csv(training.file)
test     <- read.csv(test.file)
```


## Method
features


## Results
plots, nice ones! with ggvis


## Conclusions and Limitations
