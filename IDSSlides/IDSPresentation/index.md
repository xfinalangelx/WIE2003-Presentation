---
title       : WIE2003 Group Project Presentation
subtitle    : COVID-19 Dashboard
author      : Teo Richie, Yap Gay Chin, Jovi Koh Wei Chiang, Seh Chia Shin
job         : WIE2003 FCSIT UM
logo        : covid.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

Problem Statement

> 1. How many people are being diagnosed as positive, died, or recovered from COVID-19 per day?
> 2. How did the confirmed, deceased and recovered cases evolve?
> 3. What are the specific cases by country per day?
> 4. How many countries were affected by COVID-19?

Data Acquisition

> 1. Data from John Hopkins University

Data Extraction, wrangling and analysis

> 1. Extract the data by downloading from John Hopkins University GitHub Page

> 2. Create variables such as data confirmed and data deceased and chain it with various functions



--- .class #id 

## Value Box

![ValueBox](assets/img/valueBox.png)

![CountryBox](assets/img/country.png)
#### This answers the how many people are being diagnosed as positive, died, or recovered from COVID-19 per day question in the problem statement.

---

## Map

#### By using leaflet and the reactive slider, a bubble map based on timed-series data is plotted. This answers the question of how did the confirmed, deceased and recovered cases evolve.

![Map](assets/img/map.png)
![Slider](assets/img/slider.png)

---

## Table

#### By using data table and the reactive slider, a data table based on timed-series data by country is plotted. This answers the question of what are the specific cases by country per day.
<br>
![Table](assets/img/table.png)
<br>
###### Link to GitHub repo: https://github.com/xfinalangelx/COVID-19-Dashboard 
<br>
###### Link to shinyapps: https://xfinalangelx.shinyapps.io/COVID-19-Dashboard/ 
<br>
###### Link to Assignment Report Markdown: https://github.com/xfinalangelx/COVID-19-Dashboard/blob/master/AssignmentMarkDown.Rmd 
