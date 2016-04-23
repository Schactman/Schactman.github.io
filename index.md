---
title       : Using the CHADS2 score
subtitle    : A stroke prediction tool
author      : Mark Schactman
job         : Class project
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## CHA2DS2-VASc score  
  
* The CHA2DS2-VASc score is a clinical prediction rule  
* It is used to estimate the risk of stroke in atrial fibrillation (AF) patients  
* AF is a common and serious heart arrhythmia associated with thromboembolic stroke  
* The score helps determine whether or not anticoagulation therapy or antiplatelet therapy is needed  
* A high CHADS2 score corresponds to a greater risk of stroke  
* The CHADS2 score is simple and has been validated by many studies  
* The STapp application is a simple interactive web tool to compute this risk
* https://markschactman.shinyapps.io/STapp/

--- .class #id 


## Input variables  

1. Congestive heart failure (CHF)  
2. Hypertension  
a. blood pressusre > 140/90 mmHG, or  
b. treated with hypertension medication  
3. Age > 75 years old  
4. Type 1 diabetes  
5. Prior stroke, TIA, or thromboembolism  
  
* Risk factors 1 to 4 each count as 1 point.  
* The fifth risk factor counts as 2 points.  
* Compute the score depending on a patient's risk factors  

--- .class #id 


## Web site  

![image](https://github.com/Schactman/Schactman.github.io/blob/master/STapp.PNG)  

--- .class #id 


## Example 

* Assume the following:  
** 80 year-old diabetic with heart failure  
** no hypertension  
** no prior stroke  
* This information is entered into the website and the stroke risk is computed


```
## [1] "Stroke risk: 4.6 - 7.3%"
```







