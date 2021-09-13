---
title: "Untitled"
output:
  html_document:
    toc: true
    fig_caption: true
---

## Overview

```r
hello <- "hello world"
hello
```

```
## [1] "hello world"
```


## Analysis

```r
library(readxl)
fast_food  <-  read_excel(path="./Copy of FastFoodHW.xlsx", sheet="FastFood")
summary(fast_food)
```

```
##   restaurant            item              calories         cal_fat      
##  Length:515         Length:515         Min.   :  20.0   Min.   :   0.0  
##  Class :character   Class :character   1st Qu.: 330.0   1st Qu.: 120.0  
##  Mode  :character   Mode  :character   Median : 490.0   Median : 210.0  
##                                        Mean   : 530.9   Mean   : 238.8  
##                                        3rd Qu.: 690.0   3rd Qu.: 310.0  
##                                        Max.   :2430.0   Max.   :1270.0  
##    total_fat         sat_fat         trans_fat      cholesterol    
##  Min.   :  0.00   Min.   : 0.000   Min.   :0.000   Min.   :  0.00  
##  1st Qu.: 14.00   1st Qu.: 4.000   1st Qu.:0.000   1st Qu.: 35.00  
##  Median : 23.00   Median : 7.000   Median :0.000   Median : 60.00  
##  Mean   : 26.59   Mean   : 8.153   Mean   :0.465   Mean   : 72.46  
##  3rd Qu.: 35.00   3rd Qu.:11.000   3rd Qu.:1.000   3rd Qu.: 95.00  
##  Max.   :141.00   Max.   :47.000   Max.   :8.000   Max.   :805.00  
##      sodium       total_carb        fiber               sugar       
##  Min.   :  15   Min.   :  0.00   Length:515         Min.   : 0.000  
##  1st Qu.: 800   1st Qu.: 28.50   Class :character   1st Qu.: 3.000  
##  Median :1110   Median : 44.00   Mode  :character   Median : 6.000  
##  Mean   :1247   Mean   : 45.66                      Mean   : 7.262  
##  3rd Qu.:1550   3rd Qu.: 57.00                      3rd Qu.: 9.000  
##  Max.   :6080   Max.   :156.00                      Max.   :87.000  
##    protein             vit_a              vit_c             calcium         
##  Length:515         Length:515         Length:515         Length:515        
##  Class :character   Class :character   Class :character   Class :character  
##  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
##                                                                             
##                                                                             
##                                                                             
##     salad          
##  Length:515        
##  Class :character  
##  Mode  :character  
##                    
##                    
## 
```
