
# Investigating Suicide Rate
##By Anosh.S, Stuart.T, Matteus.R and Kshitij.M

## Executive Summary

Suicide is a growing problem in many places around the globe in the 21st century. This report aims to determine whether there is a correlation between socio-economic and health factors and suicide rate through the comparison of gross domestic product, age, sex, and unemployment rate. Through the comparison of these variables, the report will explore the trends in the data to understand why the trends found exist and what is potentially driving the changes. 

Income vs Suicide Rate: A trend appeared in all 4 time periods spanning 2005-2015, there is a moderate inversely proportional relationship between suicide rate and income, especially at the upper extremities, where high suicide rates/incomes are exhibited in countries of low incomes/suicide rates, respectively.

Age & sex vs suicide rate: The last 15 years have shown a gradual decline in average suicide rate globally. This is because the 21st century society has become more aware of the causes of suicide and societal expectations have changed.

Unemployment vs Suicide Rate: Unemployment has shown to be a causal factor of suicide as it causes a loss of social status and structure, financial strain, and has a significant social stigma attached to it.


<br>


## Initial Data Analysis (IDA)

Suicide claims over 800,000 lives worldwide annually, contributing to 1.4% of deaths globally in 2016. It is a complex phenomenon, and understanding contributing factors to suicide are important in improving prevention. By comparing suicide rates across 135 countries with sex, income, and unemployment, we hope to see trends in the data which allow for an effective delineation of some of the causes of suicide. 

To compare incomes internationally, GDP (Gross domestic product) per capita is not an accurate measure, since the spending power of that income is not equal. Thus, GDP at PPP (purchasing power of parity) provides a normalised value for income, removing spending power of income as a confounding factor. Unemployment rate is an ideal statistic to use, as it represents the percentage of people willing and able to, but unable to find work, which can be linked to loss of status, social stigma and other factors increasing suicide risk.

To source our variables, multiple datasets were used sources. A World Health Organisation data set (dataset 1), containing country (factor), year (integer), sex (factor), age range (factor), suicide number (integer), and suicide rate (number)  was used to compare global suicide rate with sex and age. 
However, a second dataset (dataset 2) was used for the first and second research questions. After cleaning and shortening the time span of the investigation (to reflect the time period of recorded data), dataset 2 contained seven variables: country (factor), year (integer), sex (factor), suicide rate (number), unemployment rate (number), PPP (number), and continent/region (factor). Utilising two datasets ensured that the data was valid as the values were compared to ensure consistency.

The validity of the source was also checked for reputability. Dataset 1 was sourced from the World Health Organisation (WHO), an autonomous organisation working with the United Nations focusing on international world health.The WHO's autonomy, UN association and healthcare specialty mean the health data used is very unlikely to be false/biased. Economic data for dataset 2 was sourced from the World Bank, a financial institution with 189 member countries, aiming to reduce poverty. World Bank's economic specialty and international recognition/participation means there is little cause for manipulating economic data, making it also reliable.

<br>Stakeholders with an interest in this report include:</br> 
<br>- The health sector globally has to have the resources available to support and reduce current suicide rates. Analysing the past and present data allows governments and those who fund the health sector to make decisions on how resources and money should be allocated to effectively address the issue of suicide.</br>
<br>- The education sector plays a significant role in the reduction of suicide rates through the  education of the population on the factors that contribute to suicide.</br>
<br>- Governments have an obligation to efficiently and effectively address the needs of their people. Analysing trends of suicide rates allows governments to make the necessary changes to budgets to ensure that the issue they face as a nation is addressed and minimised.</br>
