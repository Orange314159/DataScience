
# Data Science Coursework

## Description

This project holds all of the deliverables that I have created for data science fundamentals at LASA.
This course begins with the fundamentals of python and builds up tools to do statistical analysis and model creation.
In the course I will use polars, pandas, and numpy primarily for data creation and then pymc, bambi, and a variety of other tools for model creation.
In addition I will leverage the use of packages such as matplotlib to create better visuals. 
This course is set up in a juypeter notebook format in order to allow for quick on-the-fly adjustments to code and to include commentary on my work between code segments. 
Commentary is one of the most important parts of data science, because without context and commentary the data can only tell so much of a story. 

## Deliverables and Models

Projects one and two revolve primarily around understanding of python and the tooling so there are not included models for these units.

### Unit 3 Project

In this project I study the sleep of some of my classmates and attempt to create a model that will follow their sleep. Here is my created model using a heirarchy of priors.

![Project_3_PPC](/Photos/proj3_ppc.png)

Here we can see the posterior predictive created beased on the observed sleep data. The x-axis represents sleep measured in hours and the y-axis represents frequency. 

### Unit 4 Project

In this unit I improve upon my previous work in unit three and following a similar idea as last time, but using other student sleep data as further priors.

![Project_4_PPC](/Photos/proj4_ppc.png)

This is not a clear improvement which goes to show that even with more data does not come better models or more realistic approximations.

### Unit 5 Project

In this unit I move away from looking at sleep because there is not very much data in this area. I use a data set of stock prices from RGTI and RGTIW in this unit to compare how well these stock prices follow each other.

![Project_5_Fit_Line](/Photos/proj5_fit_line.png)

This line demonstrates the similartity of the two stock models, and using this we are able to create a very well fitting ppc. 

![Project_5_PPC](/Photos/proj5_ppc.png)

### Unit 6 Project

In this project I move to a possibly more intresting data set of looking at Nvidia stock price. In this unit I look into using 3-8 priors and implementing ELPD_loo to compare these models. 

![Project_6_ELPDLOO](/Photos/proj6.png)

In this diagram we can see how ASML, SK Hynix, TSMC, and AMD are the best predictors of the Nvidia stock price. 