# R Lab: Income Inequality Analysis (OECD Data)

![](https://upload.wikimedia.org/wikipedia/sco/0/0d/OECD_logo_new.svg)


The gap between rich and poor keeps widening. Growth, if any, has disproportionally benefited higher income groups while lower income households have been left behind. This long-run increase in income inequality not only raises social and political concerns, but also economic ones. 

In this lab, we use the latest OECD data on income inequality to check wether the previous statemts can be confirmed.  

*Income* is defined as household disposable income in a particular year. It consists of earnings, self-employment and capital income and public cash transfers; income taxes and social security contributions paid by house-holds are deducted. The income of the household is attributed to each of its members, with an adjustment to reflect differences in needs for households of different sizes. 

Income inequality among individuals is measured here by the **Gini coefficient**. The Gini coefficient is based on the comparison of cumulative proportions of the population against cumulative proportions of income they receive, and it ranges between 0 in the case of perfect equality and 1 in the case of perfect inequality. 

[Source: OECD (2018)](https://data.oecd.org/inequality/income-inequality.htm)

## Task description

a. Drop the following variables: INDICATOR, SUBJECT, MEASURE, FREQUENCY, Flag Codes. If necessary, convert variables.


b. Identifiy and report (value, country and year) the lowest and highest Gini value in the dataset. 


c. Identifiy the country with the highest variation in the Gini coefficient (hint: use interquartile range) and create a barplot (with x=TIME). 


d. Select all data with a Gini coefficient value lower than 0.245 an save the data as a new dataframe (gini_lower).


e. Calculate the mean, median, standard deviation and interquartile range for locations: 
        Germany (DEU), Norway (NOR), France (FRA) and Costa Rica (CRI) and interpret your findings


f. Create a Boxplot for:
  1) All countries
  2) only the country with the highest variation
  3) the countries fromn e) (in one plot)
