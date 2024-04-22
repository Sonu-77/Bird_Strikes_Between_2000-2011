# Bird Strikes between 2000-2011


#### This project aims to generate insight for the online sales and offline sale from all over the country to provide the business oweners the overviews of there business. The important part is the owners can analyse the growth or downfall by using the interactive dashboard.

## Table Of Content 
- [Tools Used](#tools-used-while-performoing-the-analysis)
- [Data Cleaning](#data-cleaning-step-used-in-python)
- [EDA](#performed-the-eda-in-python)
- [Dashboard in Tableau](#using-the-cleaned-dataset-performed-interactive-dashboard-in-tableau)
- [Result](#result-and-findings)
- [Conclusion](#conclusion)

## Tools Used While performoing the Analysis
- Excel - [Download Dataset Here](https://docs.google.com/spreadsheets/d/1PF1PQ4-qg4ySrtyOXiF6SFGX7P0Qfl_r/edit#gid=1443108996)
- Python
  - Jupyter notebook - Cleaning the dataset and showing the graphical visualizations.

- Tableau - Created an interactive dashboard for analysising all the outcome.
  

## Data Cleaning Step Used In Python 
- imported the necessary libraries.
- loaded the csv file from the system.
- performed the cleaning analysis:
  - Removing duplcates.
  - Replacing/Droping the Null/NA values.
  - adjusted the dtypes of date and time columns.
  - droped the unnecessary columns to remove confuctions

## Performed the EDA In Python:
- Top 10 Birds Struck on the following Airport 
- Bar plot for Birds Struck at Diff. Altitude
- Distribution Category Wise Birds Struck
- Pie Chart to show the Birds struck by Aircraft Models
- Impact to Flight Caused by Birds Struck
- Different Graphs for Showing Insight of Cost, People Affected & Weather Conditions


## Using the cleaned dataset performed Interactive Dashboard in Tableau
-[Tableau Dashboard](https://public.tableau.com/app/profile/sonu.kachhap)


## Result and Findings
- The highest no. of  Birds strucks on the Airports was  DALLAS/FORT WORTH INTL ARPT with an count of "2932", as the barplot show the other Airports with there birds struck's count.
- The barplot shows the frequency of the Bird's strucks on different altitude as the highest count is shown by the altitude less then 1000ft with a count of "59270" on the Range of one decade.
- The plot one shows the sum of each category and the highest sum falls in (2 to 10) with sum of "25513".
- The plot two shows the count of each category  and the highest  count falls in (1) with count of "20610".
- The pie chart shows the models with the highest no. of birds struck by each Aircraft models, as the highest no. of birds struck by the model is CL-RJ100/200 with count of "5878". and share 17.87% of the top 10 models in the chart.
- The Pie chart plots that the impact to the Aircraft was vey less or "Nothing" where as there was few portions shown in the pie chart  the impact was caused like "Engine Shut Down,Precautionary Landing & Others"
- Plot One shows the cost affected by the types of different bird species struck, as the expence is high when the brid species struck is "Large" with "58.2%" share in pie chart.
- Plot Two shows the Donut chart with the people affected by the different bird species struck as the figure is wide when the bird species was "Large" with "47.6%" and sum is 10.
- Plot Three shows the lineplot where this shows the total no. of birds struck by different weather conditions, the highest no. of birds struck was when the weather condition was "Rain" with the total of "4374" and lowest when "Fog,Snow" with the total of "4".


## Conclusion
- The analysis of bird strike data highlights a critical balance between safety and wildlife conservation. As strikes pose risks to both aircraft and birds, it is imperative to prioritize sustainable practices to protect avian species. Without intervention, we risk not only endangering these species but potentially leading them to extinction. Proactive measures must be taken to safeguard their populations for the ecological balance and the well-being of our shared environment.
  












