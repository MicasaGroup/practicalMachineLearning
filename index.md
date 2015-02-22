---
title       : Practical Machine Learning 
subtitle    : This write up is a slidify slide deck. Please use arrow keys to move to the next page
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction
### Goal of assignment
Using data from the Weight Lifting Exercise Dataset (provided by Human Activity Recognition), develop a prediction model to predict the manner in which an exercise is performed.

### Deciding the predictors

The test data provided has the following has the following dimensions:

```
## [1] 19622   160
```
A check of missing values in the data frame shows:
```{ r echo=FALSE}
propmiss(pmltraining)
```

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!


--- .class #id 

## St




