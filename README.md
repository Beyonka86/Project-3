# Project 3 Global Health Analysis - Data Representation Track
________________________________________________________________
# Group Name
________________________________________________________________
The Age of aQueryus

# Group Members
________________________________________________________________
* Matt Zavala
* Beyonka Powell
* Leanne Novo

# Datasets for reference
___________________________________________________________________
* World Happiness Report 2024
* GBD 2019
* OECD.org Educational attainment and labor force status

# Libraries used
___________________________________________________________________
* pandas
* plotly/plotly.io/plotly.graph_objects/plotly.subplots
* matplotlib
* mongodb
* os
* scipy stats
* numpy
  
# Introduction
_____________________________________________________________________
The goal of this research project is to utilize data visualization methods to assess whether there are patterns between select happiness metrics from World Happiness Report (WHR 2020), the varying prevalence of the top 3 causes of death (Global Burden of Disease 2020), and average levels of education per country (OECD 2020). Our group draws inspiration to pursue this project from the reports themselves - the specificity of phenomena assessed within each report are simultaneously factors we hypothesized to influence each other. Hence, our group’s goal is to uncover any relationships across these three datasets and convey our findings through data representation. Each team member will address one of the three research questions outlined below:
___________________________________________________________________________
# Matt-- Does attaining a higher level of education correlate to being more happy?

![freedom to make life choices vs  avg edu](https://github.com/Beyonka86/Project-3/blob/main/Matt_PNG/freedom%20to%20make%20life%20choices%20vs.%20avg%20edu.png)

In this visualization we see the correlation between Average Years of Education Achieved from (OECD 2020) and the Freedom to Make Life Choices (WHR 2020). A very weak positive correlation exists between the two factors with an R-Squared = 0.07. It appears that while the citizens of about 75% of the world's countries have the freedom to make their own life choices, that choice does not always correlate to pursuing a higher education.In this visualization we see the correlation between Average Years of Education Achieved from (OECD 2020) and the Freedom to Make Life Choices (WHR 2020). A very weak positive correlation exists between the two factors with an R-Squared = 0.07. It appears that while the citizens of about 75% of the world's countries have the freedom to make their own life choices, that choice does not always correlate to pursuing a higher education.

![Life expectancy vs  avg edu](https://github.com/Beyonka86/Project-3/blob/main/Matt_PNG/Life%20expectancy%20vs.%20avg%20edu.png)


This visualization shows strong positive correlation between Average Healthy Life Expectancy (WHR 2020) and Average Education Attained (OECD 2020) per country with R-squared = 0.52. As expected, we see more developed countries at the top end of this visualization. These countries often have better access to healthcare, higher standards of living, and greater awareness of healthy lifestyle practices. Environmental factors, cultural norms, diet and exercise, and more all play a part in a long and healthy life, but this visualization shows that education also plays a role in contributing to overall longevity, in turn, contributing to a greater sense of happiness.


![Social support vs  avg edu](https://github.com/Beyonka86/Project-3/blob/main/Matt_PNG/Social%20support%20vs.%20avg%20edu.png)

Social support is defined in the World Happiness Report as a binary response to the question, "If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?"

This visualization shows correlation between social support and education achieved globally. Again, we have a strong positive correlation with an r-squared value of 0.52. This plot shows that having a stronger social network correlates to finding more opportunities for education. Being more mentally healthy, building healthier habits, and finding more fulfillment in community engagement are all benefits of being more socially connected.


___________________________________________________________________________
# Beyonka-- Does attaining a higher level of education correlate to lower cause of death prevalence?

![Road Injuries vs  Average Education by Location](https://github.com/Beyonka86/Project-3/blob/main/Beyonka_PNG/Road%20Injuries%20vs.%20Average%20Education%20by%20Location.png)

The first graph depicting the rate of road injuries within the top 3 causes of death (Global Burden of Disease 2020) and average years of education by location encompassing countries around the world demonstrates a slight negative correlation, with a range of 0.05 to 0.1. The data suggests that higher average years of education correspond to lower incidences of road injuries. As the incidence of road injuries increases, fewer countries are represented. Specifically, Saudi Arabia and Qatar emerge as two countries with the highest death rates for road injuries per 8 to 9 years of education. Saudi Arabia and Qatar's moderate average years of education coupled with higher road injuries could be influenced by various factors and should not be seen as a causal relationship. Perhaps these countries prioritize other areas of education or have different educational systems focusing less on road safety. Socioeconomic factors, infrastructure quality, and cultural norms regarding road safety hold influence as well. It's essential to consider the broader context- government policies, economic development, and societal attitudes, to fully understand the correlation between education and road injuries.

![HIV vs  Average Education by Location](https://github.com/Beyonka86/Project-3/blob/main/Beyonka_PNG/HIV%20vs.%20Average%20Education%20by%20Location.png)


The second graph illustrates the relationship between HIV incidence and average years of education. We observe a positive correlation between HIV incidence and average years of education. As the level of education increases, the HIV incidence tends to decrease. Conversely, areas with higher HIV incidences are associated with lower levels of education, typically ranging from 4 to 12 years. These countries are often clustered geographically, indicating proximity of HIV prevalence in certain regions. Some reason for the high cases of HIV in these countries are due education systems may not adequately address topics related to sexual health, HIV prevention, and safe practices, socioeconomic disparities which limits access to healthcare, and inadequate infrastructure, can exacerbate the spread of HIV or cultural and societal norms which can prevent behaviors related to HIV prevention and testing.

![Ishemic Heart Disease vs  Average Education by Location](https://github.com/Beyonka86/Project-3/blob/main/Beyonka_PNG/Ishemic%20Heart%20Disease%20vs.%20Average%20Education%20by%20Location.png)

The third graph depicts the correlation between Ischemic Heart Disease and average years of education. While a subtle positive correlation is evident between the two factors, no discernible relationship is observed with increasing levels of education to show any decrease of incidence to Ischemic Heart Disease.

__________________________________________________________________________________________
# Leanne-- Does disease prevalence have an impact on a country’s happiness?

Rates of the top 3 causes of death (Global Burden of Disease 2020) were compared against all measures of the World Happiness Report and average levels of education per country (OECD 2020) to assess whether there were any correlations between the variables. As there are 7 variables in this analysis, a scatter matrix was generated in order to view overall patterns at first glance:

![3DeathWHR](https://github.com/Beyonka86/Project-3/blob/main/Pictures_LN/3DeathWHR.png)

The most informative section of the scatter matrix as it relates to the research question falls in the diagonal selection of twelve charts between “Road Injuries, Logged GDP per Capita” and “Ischemic Heart Disease, Freedom to make life choices.” The patterns are most similar to each other when grouped by the rates of top 3 causes of death.

![RoadInjury](https://github.com/Beyonka86/Project-3/blob/main/Pictures_LN/RoadInjury.png)

Across the various measures being tested against road injury death rates, weak correlations exist at almost R-squared = 0 for each measure. There appears to be no relationship that can be inferred between the rate of death due to road injury and the other factors. Saudi Arabia is listed as the country with the highest death rates for Road Injuries.

![HIV](https://github.com/Beyonka86/Project-3/blob/main/Pictures_LN/HIV.png)

Similarly weak correlations also exist amongst the various measures being tested against rates of death due to HIV. No correlational relationship can be assigned to rates of death due to HIV and the other factors. The countries bearing the highest rates of HIV listed in the graph are primarily located in Africa.


![IHD](https://github.com/Beyonka86/Project-3/blob/main/Pictures_LN/IHD.png)

If a regression analysis using a log-transformed fit is used for this representation, there may be a stronger correlation between the variables measured against rates of death due to ischemic heart disease. Yet, the correlation remains weak across the variables in this representation and no relationship can be inferred. In this view, Kuwait holds the highest Ischemic Heart Disease-related death rate.

Given that the patterns are most similar to one another when grouped by the cause of death, there are likely a series of un-assessed factors mentioned in the previous questions contributing more significantly to the outcomes seen across the causes of death.

______________________________________________________________________
