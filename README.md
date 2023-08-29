# Hi! Welcome to the Regression Modelling in R course! :grinning: :chart_with_upwards_trend:

#### We're Sonja and Fernando, two PhD students at the Imperial School of Public Health :hospital:, and we'll be teaching this interactive, standalone, and roughly 3-hour course for the Graduate School in-person in the Central Library :books:. We highly recommend that you bring your own laptop :computer: to class and follow the pre-course setup below before coming to the workshop!

## 1. Pre-course setup :computer:
Hit the :green_square: <> Code button above and select "Download ZIP" to get all of the contents of this repository (Powerpoint slides, R code, HTML document, and other fluff). 

Next, as we will be working with the open-source (a.k.a. free :partying_face:) programming language "R" and the integrated development environment RStudio. Please download and install these in advance of the session to save yourself the hassle during the course:

:arrow_right: R (download the version that matches your operating system): https://cran.ma.imperial.ac.uk/  
:arrow_right: RStudio Desktop (the free version): https://posit.co/downloads/

Once downloaded, please copy and paste the following code into your "Console" in RStudio and run it by hitting "Enter" to install the required packages for the session:
```r
list.of.packages <- c("faraway")
new.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
if(length(new.packages)) install.packages(new.packages)

library(faraway)
```
Alternatively, you can run the R code that we'll be working with online using Binder (although we do not recommend doing this using the classroom computers as they're very slow): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ImperialCollegeLondon/RCDS-regression-modelling/HEAD?urlpath=rstudio)

## 2. Literature workshop :page_facing_up:
For the workshop, we will be interpreting the results from this paper by Sin *et al.* titled "Mental health and caregiving experiences of family carers supporting people with psychosis". We will give you enough time to read through the abstract and interpret the result tables during the session, but you may get a headstart by doing this in advance: [link to paper](https://www.cambridge.org/core/journals/epidemiology-and-psychiatric-sciences/article/mental-health-and-caregiving-experiences-of-family-carers-supporting-people-with-psychosis/FF705DECFAC216D777B834E5D2A0180F).

## 3. Learning outcomes :bulb:
By the end of this course, we hope that you will be able to:
1. Define and explain fundamental concepts of regression modelling.
2. Formulate, apply, and compare regression models based on a research question.
3. Estimate regression coefficients using R and interpret them in the context of the question.
4. Interpret regression model results from scientific papers.
