---
title       : Earthquake Visualizer
subtitle    : 
author      : Rong Xie
job         : Software Engineer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

This Shiny App is for searching and visulizating Earthquake Sets information of latest month (08-28-2015 ~ 09-27-2015 for this demo) in the US. The total number of set records is 8428 and US record is 7075. The visualizer only cares about earthquake classes equal or above Minor:

| Glass    | Magnitude |
|----------|-----------|
| Great    | 8 or more |
| Major    | 7 - 7.9   |
| Strong   | 6 - 6.9   |
| Moderate | 5 - 5.9   |
| Light    | 4 - 4.9   |
| Minor    | 3 - 3.9   |

--- .class #id

## Slide 3

# How to view the app
App:https://sharonxie.shinyapps.io/project

Data Explorer show you the original data

Data Visualize tab shows 3 content

* Earthquake by State Summary (choose the radio option in sidebar to see summary for each state)
* Occurrences Overview (an overview of occurrences of all states)
* Stats by Class

--- .class #id

## Slide 4

# Stats by Class

It allows you to see each class according to time stamp

Example:
 
 * select x Lin as Time
 * select y Lin as Occurrences
 * select color to be Unique colors
 * select size to be Occurrences
 
 Then you can see the occurrences view overtime
 swithing tab to have scatter plot, bar plot or time series plot

--- .class #id

## Slide 5

# Appendix

Reference: http://www.geo.mtu.edu/UPSeis/magnitude.html

Data Source: http://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php

Date updated: 09/27/2015

--- .class #id







