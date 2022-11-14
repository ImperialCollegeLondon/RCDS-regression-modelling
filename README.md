# Hi! Welcome to the Regression Modelling in R course! :grinning: :chart_with_upwards_trend:

#### We're Sonja and Fernando, two PhD students in the Imperial School of Public Health :hospital:, and we'll be teaching this interactive, standalone, and roughly 3 hour course for the Graduate School in-person in the Central Library :books:.

## 1. Learning outcomes :bulb:
By the end of this course, we hope that you will be able to:
1. **Identify** the correlation coefficient as a single measure of a linear association.
2. **Apply** general linear models to model a response variable in terms of a single or multiple variables.
3. **Assess** model validity by checking model assumptions.
4. **Evaluate** model fitness by comparing the results produced by the model with your data.
5. **Present** model fitness using data visualisation techniques.
6. **Interpret** regression model results from scientific papers.

## 2. Pre-course setup :computer:
We will be working with the open source (meaning free :partying_face:) programming language "R" and the integrated development environment (IDE) RStudio. Please download and install these in advance of the session to save yourself the hassle during the course.

:arrow_right: R (download the version that matches your operating system): https://cran.ma.imperial.ac.uk/  
:arrow_right: RStudio Desktop (the free version): https://posit.co/downloads/

## 3. Course materials :book:
Please run the following code to install the required packages for the session:
```r
list.of.packages <- c("faraway", "viridis", "tidyverse", "corrplot")
new.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
if(length(new.packages)) install.packages(new.packages)

library(faraway)
library(viridis)
library(tidyverse)
library(corrplot)
```
Alternatively, you can run the notebook online using Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ImperialCollegeLondon/RCDS-regression-modelling/HEAD?urlpath=rstudio)
