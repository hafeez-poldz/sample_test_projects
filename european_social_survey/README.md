# European Social Survey Sample Tests
The European Social Survey (ESS) is an academically-driven multi-country survey, which has been administered in over 30 countries to date. 
In this dataset, the same participants answered questions in 2012 and again 2014. 

## Source: https://www.europeansocialsurvey.org/data/download.html?r=8 
## Goal: 
The goal is to compare these samples to answer the following questions:

1. Did people become less trusting from 2012 to 2014? 
2. Did people become happier from 2012 to 2014? 
3. Who reported watching more TV in 2012, men or women?
4. Who was more likely to believe people were fair in 2012, people living with a partner or people living alone?
5. How often people in different countries met socially in 2014. Are there differences, and if so, which countries stand out?
6. How often people in different countries  ook part in social activities, relative to others their age, in 2014. Are there differences, and if so, which countries stand out?

## Methods:
For each question I'll use one of the below mentioned statistics tests:

 - Parametric:
* F-test - assumes that the two samples has the same variance
* T-test - assumes that the difference beetwen samples' means are is ZERO
* Z-test - assumes that the means of two samples are not different
* One-way ANOVA - assumes that the three or more samples has the same variance
* Turkey's HSD test - assumes that the means of three or more samples are same

 - Non-parametric:
*  Mann-Whitney U-test - assumes that the two distributions are similar in shape