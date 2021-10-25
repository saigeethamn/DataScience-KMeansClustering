# DataScience-KMeansClustering

Problem Statement
An international humanitarian NGO has got a $ 10 million fuding. The CEO needs to decide how to use this money effectively and strategically. The significant choice at hand is the countries that are in dire need of aid.

We need to be able to categorise countries using some socio-economic and health factors that determine the overall development of the country.This will help the CEO to understand where to focus the most.

## Preparatory Steps

The preparatory steps are as outlined in this blog:
 https://www.saigeetha.in/post/steps-towards-data-science-or-machine-learning-models
 
## Modeling
Having done the pre-requisite transformations and data preparation, the KMeans algorithm provided by sklearn library is used and the clsuters of countries are formed based on thier health and socio-economic factors. 

## Cluster Profiling
The Cluster Profiling finally shows that 3 clusters are pretty distinct with about 48 countries falling in the cluster that is in need of aid. Amojng them, three important factors of income, child mortality and gdpp are used to decide the top 10 countries that would benefit the maximum in getting aid. 
