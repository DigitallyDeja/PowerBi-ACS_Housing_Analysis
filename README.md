# PowerBi-ACS_Housing_Analysis

This project explores U.S. housing affordability trends using ACS data, focusing on median household income, median rent, and income-to-rent gaps. It demonstrates data cleaning, KPI development, and interactive visualizations in Power BI to highlight financial strain across states.

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

## ACS Insights

- The state that has the highest Rent to Income Ratio is Florida, which is around 28%. This highlights severe affordability levels.

- Over half of households in states like Florida (~54%), California (~51%), and Louisiana (~52%) are cost-burdened, while states such as North Dakota and South Dakota remain affordable (<30%).

- After deducting the median income and average rent price, the average household has around $ 61,000 on average (pre-tax) in 2023.

- States with higher percentages of cost-burdened households often show higher MOE ratios, indicating less reliable estimates. Larger states tend to have lower MOE ratios, meaning more robust data.

## Project Takeaway

  This analysis highlights the growing challenges of housing affordability across the U.S., revealing clear state-level differences in financial strain and cost-burdened households. By combining affordability measures with statistical reliability (MOE ratios), the dashboard not only identifies where housing is least affordable but also provides context for how confident we can be in those findings. This project demonstrates the ability to transform raw ACS data into actionable insights that can support policymakers, housing advocates, and analysts in understanding and addressing the affordability crisis.

## Data Source
- American Community Survey (ACS) – U.S. Census Bureau  

