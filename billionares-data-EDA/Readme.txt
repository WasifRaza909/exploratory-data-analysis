Cleaned dataset from the Billionaires Statistic Dataset (2023) that can be found here.

The code I used to clean and re-structure the data is also here.

First things first: a big shout-out to Nidula Elgiriyewithana for providing the original data.

As with it, this dataset contains various information about the world's wealthiest persons in different columns that can be grouped into three different types:

Business-related information. These columns contain data about the industry in which the billionaires' operate, their source of wealth, total wealth and position they occupy in the ranking.

Personal information. Such as name, age, nationality, country and city of residence.
Economic activity information. These columns are related to the country in which the billionaire resides and provide different economic indicators like GDP, education enrollment or Consumer Price Index (CPI).
Column names
position. Ranking of the billionaire measured by their wealth.
wealth. The wealth of the billionaire measured in $.
industry. Industry in which the billionaire's operates their businesses.
full_name. Complete name of the billionaire.
age. The age of the billionaire.
country_of_residence. Country in which the billionaire resides.
city_of_residence. City in which the billionaire resides.
source. The source of the billionaire's wealth.
citizenship. The country of citizenship of the billionaire.
gender. The gender of the billionaire.
birth_date. The birth date of the billionaire.
last_name. The last name of the billionaire.
first_name. The first name of the billionaire.
residence_state. State in which the billionaire resides (only for billionaires who reside in the U.S.).
residence_region. Region in which the billionaire resides (only for billionaires who reside in the U.S.).
birth_year. The birth year of the billionaire.
birth_month. The birth month of the billionaire.
birth_day. The birth data of the billionaire.
cpi_country. Consumer Price Index (CPI) for the billionaire's country.
cpi_change_country. CPI change for the billionaire's country.
gdp_country. Gross Domestic Product (GDP) in $ for the billionaire's country.
g_tertiary_ed_enroll. Enrollment in tertiary education in the billionaire's country.
g_primary_ed_enroll. Enrollment in primary education in the billionaire's country.
life_expectancy. Life expectancy in the billionaire's country.
tax_revenue. Tax revenue in the billionaire's country.
tax_rate. Total tax rate in the billionaire's country.
country_pop. Population of the billionaire's country.
country_lat. Latitude coordinate of the billionaire's country.
country_long. Longitude coordinate of the billionaire's country.
continent. Continent in which the country of the billionaire's residence is located.
Potential analyses

--Analyze which industries contain the biggest groups of billionaires overall and in different countries.
--Explore number of billionaires and total wealth across countries and continents and display the result in a map.
--Focus on personal information columns such as age or gender to explore the distribution of billionaires from this perspective.
--Discover if countries' economic indicators have any impact in the presence of billionaires.
--The U.S. is the country with most billionaires presented in the dataset and also the only one with attributes in the residence_state and residence_region columns. This makes the American billionaires a good focus for a specific analysis.

Bonus
If you want a challenge, you can create a dashboard using tools such as Plotly to dynamically visualize the data using one or different attributes (such as industry, age or country). I did it, leave the link below in case you want to investigate: