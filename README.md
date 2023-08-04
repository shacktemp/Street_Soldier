# Street_Soldier

## Objective

The objective of this project is to explore the relationship between veterans receiving benefits and the homeless populations in states around the country. I will be using data from the https://catalog.data.gov/dataset/fy-2020-disability-compensation-recipients-by-county and (https://usafacts.org/data/topics/people-society/poverty/public-housing/homeless-population/?share=111873&utm_source=bing&utm_medium=cpc&utm_campaign=ND-StatsData&msclkid=98da89e8ae9318bb21a7ed550854335d).												


## Accessing the Program and Packages Needed be Installed
Find the project notebook above, street_soldier.ipynb, and run it in Google Colab. The program uses pandas and matplotlib to perform an analysis of the two mentioned data sets. It will read in, clean, and rearrange the data as needed using python commands and pandas. It will execute data visualization using matplotlib.		

## Features
1.	Read in two CSVs
2.	Clean data and perform a pandas merge. Calculate the ratio of total homelessness as compared to the VA benefit recipients for a given state.
3.	Use matplotlib to make 3 charts. A pie chart to show the relationship of veterans by their claim status. A bar chart to compare homelessness in different states. A scatterplot to display whatever overlap between homelessness and VA benefit recipients exist.
4.	Built a data dictionary that list variables and their parameters used. It is included in at the bottom of this README file.
5.	Interpretation is included in this README file.

## Data Dictionary

![image](https://github.com/shacktemp/Street_Soldier/assets/122495946/8ce890eb-c42f-46bf-a7ce-12183f8e5e22)


![image](https://github.com/shacktemp/Street_Soldier/assets/122495946/f3ca77ad-a828-47fa-863f-120af9519e24)


## Interpretation

The correlation between the number homelessness and VA benefit recipients for a given state appears to not have a strong association base on the analysis. A factor that could increase the thoroughness of this project would have been able to look at detailed homelessness data for counties. That would have allowed to better assess counties that do not have a lot of military and obviously not give a good reading for doing a comparison to homelessness populations.
