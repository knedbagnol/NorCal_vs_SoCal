# Norcal vs Socal SAT and ACT analysis
##### Kennedy Bagnol
---

## Problem Statement
---
As someone who's spent a lot of time in both Norcal and Socal I have often made comparisons between the two. This project seeks to answer the question, "Which region is smarter, Norcal or Socal?"

## Executive Summary
---
This project will explore 3 datasets, the 2019 ACT and SAT scores as well as the list of counties in Norcal and Socal.

Exploratory analysis saw the Norcal is smarter than Socal. Across the ACT, Norcal scored higher on each of the four categories and on the SAT they had a 7% higher benchmark pass rate. This pretty definitively shows that Norcal, at least on the ACT and SAT, is "smarter" than Socal. It is important to discuss the use of SAT and ACT as measures for intelligence. Many studies have been done on the correlation between wealth and success on these tests. For this reason, it is hard to say that Norcal is definitely smarter than Socal based on this as it could be more of a demographical difference. Regardless, it is interesting that Norcal outperforms Socal in this metric.


## Sources
1. [2019 ACT dataset](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)
2. [2019 SAT dataset](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent)
3. [Southern California Counties](https://en.wikipedia.org/wiki/Southern_California )
4. [Northern California Counties](https://en.wikipedia.org/wiki/Northern_California)

## Data Dictionary For Columns Used
---

|Feature|Type|Dataset|Description|
|---|---|---|---|
|norcal_counties|object|california_counties|These are the counties that make up Norcal| 
|socal_counties|object|california_counties|These are\ the counties that make up Socal| 
|pctbothbenchmark12|float|ca_sat_trim|This is the percentage of students that reached the minimum benchmark for the SAT in the 12th grade| 
|avgscrsci|float|ca_act_trim|This is the average Science score for ACT test takers in 2019| 
|avgscrread|float|ca_act_trim|This is the average Reading score for ACT test takers in 2019| 
|avgscrmath|float|ca_act_trim|This is the average Math score for ACT test takers in 2019| 
|avgscreng|float|ca_act_trim|This is the average English score for ACT test takers in 2019| 


## Conclusions
---
It was interesting to do the summary statistics at the beginning of the project which shed a light on the large population difference between Norcal and Socal. I was surprised that the SAT had twice the number of test takers as the ACT, and that Socal had twice the population of Norcal. Additionally, Norcal had 48 counties compared to Socals 10 which I think this is primarily due to geography. All of these factors affect their SAT and ACT scores, so it may not be that Norcal is necessarily "smarter" than Socal, but that Norcal has demographics more suited to doing well on the SAT and ACT.

