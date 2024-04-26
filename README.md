
# Project Data Visualisation: Historical Trends in Automobile Sales During Recession Periods

This project analyzes historical automobile sales data to understand trends during recession periods. The data includes various factors that may influence sales, such as GDP, unemployment rate, consumer confidence, seasonality, price, advertising expenditure, vehicle type, and competition. By examining these factors, we can gain insights into how recessions impact automobile sales.


## Data Description

The dataset used for this analysis contains historical_automobile_sales data representing automobile sales and related variables during recession and non-recession periods. The data includes the following variables:

- Date: The date of the observation.
- Recession: A binary variable indicating recession period; 1 means it was recession, 0 means it was normal.
- Automobile_Sales: The number of vehicles sold during the period.
- GDP: The per capita GDP value in USD.
- Unemployment_Rate: The monthly unemployment rate.
- Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
- Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
- Price: The average vehicle price during the period.
- Advertising_Expenditure: The advertising expenditure of the company.
- Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
- Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
- Month: Month of the observation extracted from Date.
- Year: Year of the observation extracted from Date.
## Installation

1- Clone this repository.

2- Install the required libraries using pip install pandas matplotlib seaborn folium.

3- Navigate to the directory containing the script(s).

4- Run the script using python <script_name.py>
    
## Analysis

We used Python libraries such as Matplotlib, Seaborn, and Folium to create various visualizations to analyze the data. Here are some key findings from the analysis:

- Overall Sales Trends: A line chart shows how automobile sales fluctuate year-to-year. This helps visualize general trends and identify potential recessionary periods.
- Sales by Vehicle Type During Recession: Line charts were used to compare sales trends between different vehicle types during recession periods. This helps identify which vehicle types are most affected by recessions.
- Recession vs. Non-Recession Sales: Bar charts were created using Seaborn to compare average automobile sales and sales of different vehicle types during recession and non-recession periods. This helps quantify the impact of recessions on sales.
- GDP During Recession: Subplots were used to compare GDP variations during recession and non-recession periods. This helps understand how economic downturns affect GDP, which can in turn impact consumer spending on automobiles.
- Seasonality Impact: A scatter plot was used to explore the relationship between seasonality and automobile sales. This helps identify any seasonal trends that may influence sales.
- Price vs. Sales: A scatter plot was used to analyze the correlation between average vehicle price and sales volume during recessions. This helps determine if there is a relationship between price and sales during economic downturns.
- Consumer Confidence vs. Sales: A scatter plot was used to explore the correlation between consumer confidence and automobile sales during recession periods. This helps understand how consumer sentiment affects purchasing decisions.
- Advertising Expenditure: Pie charts were used to visualize the distribution of advertising expenditure during recession and non-recession periods, as well as the total advertising expenditure for each vehicle type during recession periods. This helps analyze advertising strategies during economic downturns.
- Unemployment Rate vs. Sales: A line plot was created to analyze the effect of the unemployment rate on vehicle type and sales during the recession period. This helps identify how unemployment impacts sales of different vehicle types.
- Sales by Region: A choropleth map was created using Folium to visualize the highest sales regions/offices of the company during the recession period. This helps identify areas with strong sales performance during economic downturns.
## Conclusion

By analyzing historical automobile sales data with various factors, we gained insights into how recessions impact sales. The analysis revealed that recessions generally lead to a decline in automobile sales, with some variation depending on factors such as vehicle type, price, and consumer confidence. The findings from this analysis can be valuable for developing strategies to mitigate the impact of recessions on automobile sales.