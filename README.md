# PowerBi-ACS_Housing_Analysis

This project explores housing affordability trends in the U.S., focusing on **median household income, median rent, and income-to-rent gaps**. It demonstrates **data cleaning, KPI calculation, and interactive visualizations** using Power BI.  

## Datasets Used
- <a href="https://github.com/DigitallyDeja/PowerBi-ACS_Housing_Analysis/blob/main/income_percentage.csv" target="_blank">Number of Cost Burdened Households</a>

- <a href="https://github.com/DigitallyDeja/PowerBi-ACS_Housing_Analysis/blob/main/state_median_income.csv" target="_blank">Median Household Income</a>

- <a href="https://github.com/DigitallyDeja/PowerBi-ACS_Housing_Analysis/blob/main/median_gross_rent.csv" target="_blank">Median Rent</a>

## Questions KPIs 
### Summary KPI cards
- What is the national average rent price?
- What is the average median household income?
- What is the percentage of households that are cost-burdened nationally?

### Core KPIs 
- Which states face the heaviest financial strain when the median income is allocated towards rent
- How does the distribution of households across cost-burden levels (<30%, 30-50%, 50%+) depict financial vulnerability?
- How much median income remains after paying annual rent?
- How reliable are the ACS estimates according to the Margin of Error amounts?

## Process 
- Verify data for any missing data and anomalies, and transform data in Power BI
- Made sure that the data is consistent with respect to the data type, data format, and values used 
- Created charts according to the KPIs asked for and ensured that the dashboard accurately highlights this
  
## Key Skills Demonstrated
- **Data Analysis & Cleaning**: Merged multiple ACS datasets and handled missing or inconsistent values.  
- **Power BI Visualizations**: Created column, bar, scatter, and waterfall charts to highlight key insights.  
- **Calculated Metrics & Measures**: Developed **Income-to-Rent Gap** and **MOE ratios** to quantify uncertainty.  
- **Insight Communication**: Designed visuals and KPIs that clearly convey housing cost burdens.

## ACS Insights

- The state that has the highest Rent to Income Ratio is Florida, which is around 28%. This highlights severe affordability levels.

- The majority of households are cost-burdened (50% or more). This means that housing in states such as Florida, ~54%, California, ~51%, and Louisiana, ~52% more cost burden, and in North Dakota, ~50% the cost burden is the lowest amongst all states (<30%), which shows that it’s affordable.

- After deducting the median income and average rent price, the average household has around $ 61,000 on average (pre-tax) in 2023.

- Some states show a higher percentage of Margins of Error (MOE), which aligns with the higher percentages of cost-burdened households. The findings show that the higher the MOE, the less reliable the data is for the state, and a lower MOE indicates the accuracy of the data.


## Data Source
- American Community Survey (ACS) – U.S. Census Bureau  

