# Estimation of changes in air pollution during the COVID-19 outbreak
## Background:
The lockdown response to coronavirus disease 2019 (COVID-19) has caused an unprecedented decrease in global economic and transport activity. The movement of people and the corresponding activities of production and consumption have been significantly reduced. As a possible side effect of this reduction, air pollution in many areas may have been greatly reduced. Our group aim to estimate and visualize changes in air polluton during the COVID19.
## Objectives:
* We will look at the air pollution of four cities that have all been affected by COVID-19 at different levels. 
  From our initial discussion, we have selected the following: London (United Kingdom); New Delhi (India); Zurich (Switzerland).
  In details, we will look at changes in concentrations of NOx, NO2, PM, O3, VOC, NH3.
* We will look at the changes in the community mobility of these four cities before and after COVID-19.
* We aim to comparatively explore the changes in air pollution of these cities, comparing and contrasting the levels of ‘lockdown' measures put in place by local governments. 
* We will create informative visualisations to tell the COVID story, in addition to using ML techniques to understand the most significant factors of air pollution within the pandemic. Whilst we may have initial hypotheses, the data will speak for itself.

## Question/purpose: 
* Did the decrease in mobility in London, Zurich and Delhi cause any improvements in air quality in these respective cities?

## Background and prep for project: 
* A lot of research has been devoted to the impact of the COVID-19 pandemic on everything around us – from mental well-being to the economy to the environment. An interesting finding is that the decrease in industrial activity as well as transportation caused by the pandemic has decreased the levels of pollutants in the air. Some possible measures of air quality are the levels of PM2.5 (Google: “atmospheric particulate matter that have a diameter of less than 2.5 micrometers”) and NO2 (Nitrogen dioxide, Google: “emissions related to the burning of fossil fuels from [i.a.] vehicles”)
### How did we prepare for the project: 
* We wanted to assess the pandemic’s impact on the environment, which could range from the presence of wildlife/certain animal species in certain areas to air quality. For the scope of this assignment and the data available, we decided to go for analysing if and how change in mobility impacted the air pollution levels. We chose London as that is relevant to all of us and then Zurich as a city that has better air quality and Delhi as a city that has worse air quality.
### What sources of background readings did we consult: academic as well as news articles.

## Methodology: 
* First gathered reliable data sets on mobility (Google mobility data) and air pollution (website). Second, did some exploratory data analysis regarding the two data sets separately. Third, looked into correlation between the variables in the mobility data set and the variables in the pollution data set: we found that the mobility data is mostly correlated with levels of NO2 and so we decided to move into modelling air pollution by NO2 (rather than for example PM2.5 which has also been researched in the pandemic’s context). Fourth: ran ML techniques, namely decision trees and random forests and found that random forests best model the relation between mobility and NO2.

## Results and conclusion: [Selin & Kushal part]

## Discussion and critique: 
* We chose the ML techniques because these gave better results than any regressions that we tried (for example an AR(p) model). The first critique here is that such ML modelling techniques are usually more of a ‘black box’ compared to statistically solid techniques like OLS. When starting our analysis, we really wanted to find a strong relation between mobility and air pollution, as many other research articles presented. However, our results were less strong than what we had hoped for, and so we had to force ourselves to not keep on looking and thereby almost creating a stronger relation ourselves. This is actually a good learning point to be open to what the data tells us, rather than what we want to ‘tell the data’ – i.e. what we want the modelling outcomes to be. Some limitations that might have led to the lack of strength of our results might be that we had too little data / missed certain variables that made other research on this topic more significant.
What advice would you give future students: Be open/receptive to what the data tells you rather than forcing your hypotheses onto your models. If you cannot back up certain aspects of your models or validate any results you got, then that means that your hypothesised patterns/relations might be less strong or even absent or the opposite.

## Datasets:
[Air quality data](https://openaq.org/#/locations?_k=ggbbh8)
[COVID-19 Community Mobility Report Data](https://www.google.com/covid19/mobility/)

