# A Beautiful Read Me - Lab 1 - Week 4
by [Zeyad ElMahdy](https://github.com/zeyadelmahdy)

![Photos](https://github.com/zeyadelmahdy/ReadMePractice/blob/main/Photos/abeautifulreadme.png)

## Analysing Student Performance in USA Highschool




## Table of content

- [Analysis Overview](#analysis-overview)
- [Methodology](#methodology)
- [Visualization](#visualization)
- [Findings](#findings)



## Analysis Overview

Task at hand: We are presented with a dataset from an unknown highschool in the USA that includes test scores and certain categorical features for each student (race, gender..) The task is to present initial highlights/insights found in data on each category.
- You can view the raw data [here](https://github.com/zeyadelmahdy/ReadMePractice/blob/main/Data%20and%20Python%20Code/StudentsPerformance.csv)


## Methodology

First we had to import all the necessary packages, see below

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt 

```

Next, we had to import the raw data into Jupyter so we can start analysing it. 
Once we had the data, we did some cleaning by 
- Isolating the numerical values and
- Creating the overall mean value of scores

This allowed us to get the full picture when comparing test scores



## Visualization 

Below you will find an overview of graphs that will help visulize our findings. 

![Photos](https://github.com/zeyadelmahdy/ReadMePractice/blob/main/Photos/download.png)
![Photos](https://github.com/zeyadelmahdy/ReadMePractice/blob/main/Photos/download%20(1).png)

- For more visulizations, please see the original Jupyter Notebook [here](https://github.com/zeyadelmahdy/ReadMePractice/blob/main/Data%20and%20Python%20Code/Student%20Performance.ipynb)

## Findings

Based on our analysis, these are the initial insights that we deciced to present

-  Race groups scoring for math scores separated by gender = Group E is the highest scoring for both Males and Females
-  Group A is the lowest scoring across all races
-  Overall, females have scored more than males (obviously)
-  People with a masters education have scored higher on average





