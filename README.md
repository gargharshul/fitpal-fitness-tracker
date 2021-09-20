# MGMT 590-URA (Using R For Analytics) - FitPal: A Fitness Tracker

This repo contains the code for final project in the Summer 2021 edition of MGMT 590-URA (Using R For Analytics) namely FitPal App . 

## 1.Overview 

![image](https://user-images.githubusercontent.com/84420303/133953775-a3ed332b-1989-4f1e-9462-120085b66a96.png)

We have created an app that displays health data, predicts whether the user will meet their fitness goals, and prescribes recommendations on how to obtain those goals based on the user’s progress. The health and fitness industry is one of the world’s largest and fastest growing. This app uses data to allow consumers to set and meet their goals and allows us to capitalize on the demand for fitness technology. We created this app by intaking consumer data as tracked on their fitness device (Fitbit, Apple Watch, etc.) and we use R’s Shiny package to display their fitness progress.   We have created an app that displays health data, predicts whether the user will meet their fitness goals, and prescribes recommendations on how to obtain those goals based on the user’s progress. The health and fitness industry is one of the world’s largest and fastest growing. This app uses data to allow consumers to set and meet their goals and allows us to capitalize on the demand for fitness technology. We created this app by intaking consumer data as tracked on their fitness device (Fitbit, Apple Watch, etc.) and we use R’s Shiny package to display their fitness progress.   

## 2.Architeture

![image](https://user-images.githubusercontent.com/84420303/133953809-ee820463-f440-4e85-8939-5961a3355c7d.png)

The app is divided into two sections UI code and the server code. The UI code is written in pure HTML,CSS and Javascript while the server code is written in R. Finally, the app is deployed over R shiny server.
# 3.Steps to Use App

![image](https://user-images.githubusercontent.com/84420303/133953825-7848e9f4-e216-440f-af0b-7f9244dfa3ce.png)

The app can be accessded easily using the 3 simple steps shown in the image

## 4.Access the deployed App 

The deployed app is accessible -

Landing page using HTML : https://fitpalapp.shinyapps.io/home/

Main app developed using R Shiny : https://fitpal.shinyapps.io/fitpa/

## DEPENDENCIES:

```python

library(shinythemes)
library(shiny)
library(shinyWidgets)
library(shinydashboard)
library(dashboardthemes)
library(dplyr)
library(DT)
library(ggplot2)
library(XML)
library(reshape2)
library(lubridate)
library(scales)
library(ggthemes)
library(ggrepel)
library(plotly)
library(readxl)
library(bslib)
library(writexl)
library(tidyr)
```

