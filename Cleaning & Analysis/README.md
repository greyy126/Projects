The dataset contains information on global suicides, with details such as the number of suicides, GDP per capita, and Human Development Index (HDI) for various countries.

**Summary:** 

Handling Missing Values:
Checked for and displayed the count of missing values in each column.

Data Cleaning:
Dropped the 'country-year' column
Renamed the column ' gdp_for_year ($)' to 'gdp_for_year($)' for easier access.
Applied a custom function remove_num to handle scientific notation in the 'gdp_for_year($)' column.
Removed unwanted characters in the 'gdp_for_year($)' column for easier conversion.

Data Type Conversion:
Converted 'suicides_no' and 'gdp_for_year($)' columns to integers using astype(int).
Checked and converted 'gdp_per_capita ($)' to two decimal places.
Rounded 'suicides/100k pop' and 'HDI for year' columns to three decimal places for better understanding.

**Analysis (Using Tableau Dashboard):** 
The dashboard is titled "Suicide Rates Dashboard" and it shows data on suicide rates by country, year, and gender. The top of the dashboard shows the average number of suicides for females and males, with 7,255,979 for females and 7,178,929 for males. The bar can also be used as a filter for the rest of the graphs to determine the difference between males and females.

The left side of the dashboard shows a graph of suicide rates by country. The colors on each part of the map describe the number of suicides in that particular continent. The highest number of suicides is recorded in Russia with a sum of 1,241,820.

The right side of the dashboard shows a graph of suicide rates about generation-wise distribution. 
Suicide rate as per the average generation population:
Gen z - 0.08
Gi - 0.02
Boomers - 0.07
Millennials - 0.3
Silent - 0.1
Gen x - 0.08
As per the above table, millennials have the highest suicide rate.

The bottom of the dashboard shows a graph of yearly trends. According to the line chart, the year 1995 peaked in terms of suicide per 100k population.

Overall, the dashboard shows that suicide rates are higher for males than females and that they have been kind of decreasing for both males and females in recent years. 

Tableau Visualization link : https://us-west-2b.online.tableau.com/#/site/datavismadison/views/AnalysisonSuicideRatesDashboard/Dashboard1 
