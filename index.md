---
title       : Body Mass Index Classification
subtitle    : Developing Data Products Course Assignment
author      : Sherif EL Farahaty
job         : Consultant
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

Body Mass Index (BMI) is a simple index of weight-for-height that is commonly used to classify underweight, overweight and obesity in adults. It is defined as the weight in kilograms divided by the square of the height in metres (kg/m2).

# Key Facts:

1. Worldwide obesity has nearly doubled since 1980.
2. In 2008, more than 1.4 billion adults, 20 and older, were overweight. Of these over 200 million men and nearly 300 million women were obese.
3. 35% of adults aged 20 and over were overweight in 2008, and 11% were obese.
4. 65% of the world's population live in countries where overweight and obesity kills more people than underweight. More than 40 million children under the age of 5 were overweight or obese in 2012.

--- .class #1

## Body Mass Index Classification BMI-C Application

Following is the screen shoot from the application
<div style='text-align: center;'>
    <img height='400' width='800' src='BMI_Screen.png' />
</div>

In order to access the App of BMI-C [click here]

[click here]: <https://tkeshfa.shinyapps.io/BMI-Classification>

--- .class #2

## Instrcution on using the BMI-C

The user is required to enter height in centimeters and weight in kilograms.
For measurments in Imperial Units please use following conversions:

> 1 Foot [ft.] = 30.48 Centimeters [cm.] 

> 1 Inch [in.] = 2.54 Centimeters [cm.]

> 1 Pound [lbs.] = 0.4536 Kilograms [kg.]

> 1 Stone [st.] = 6.35 Kilograms [kg.]

Then Press "Go!" Button 

--- .class #3

## BMI-C Feature "Mean BMI Trend"

This feature shows the BMI trend graph for a selcetd country split by Male & Female. Following is an Example for Canada.


```
## <iframe src=' assets/fig/unnamed-chunk-1-1.html ' scrolling='no' frameBorder='0' seamless class='rChart highcharts ' id=iframe- chart2f0413543e87 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>
```

--- .class #4

## BMI-C Feature "BMI Indicator for US"

This features shows the BMI distribution chart among Under Weight, Normal Weight, Over Weight and Obese indicators. Following is an example for Alaska State in USA.

<div style='text-align: center;'>
    <img height='400' width='800' src='BMI Indicators for USA.png' />
</div>


Please note that this feature is applied only if USA is selected as a country


