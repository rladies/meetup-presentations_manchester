---
title: "Introduction to R"
author: "Tatjana Kecojević"
date: "2016-11-12"
output: html_document

---



## R 

The purpose of this section is to provide a basic overview of and introduction to R language and its environment for statistical computing and graphics. R is a public domain language for data analysis, fast becoming the lingua franca of quantitative research with some 9220 free specialised packages. R is a free, open-source data analysis package available for Windows, Mac OS X, and Unix/Linux systems, develop  ed and maintained by R Development Core Team. You can download R from: <http://cran.r-project.org>.

## Getting Started

To run R you need to click on the R icon on your computer. When R is launched you will see a single window called R Console 

![Figure 1: R Console](R_Console.png)

(Figure \ref{Fi:R_Console}).


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

## Including Plots

You can also embed plots, for example:

![plot of chunk pressure](figure/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
