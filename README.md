# Athletic Footwear and Apparel Sales Analysis 
## Overview
This assignment involves combining and cleaning two Athletic Sales datasets from 2020 and 2021. The combined dataframe was analyzed to determine which regions, states, cities, and retailers performed best in various sales metrics. The analysis focuses on general sales, and specifically on sales of women's athletic footwear.


## Requirements
The project is divided into 6 main parts:
1. **Combine and Clean the Data:** Used an inner join to combine the two DataFrames along the rows.
2. **Determine which Region Sold the Most Products:** used both groupby or pivot_table to segment data by "region", "state", and "city". Calculated the sum of total products sold using units sold values. 
3. **Determine which Region had the Most Sales:** used both groupby or pivot_table to segment data by "region", "state", and "city". Calculated the sum of total sales using total sales values.
4. **Determine which Retailer had the Most Sales:** used both groupby or pivot_table to segment data by "retailer","region", "state", and "city".  Calculated the sum of total sales using total sales values.
5. **Determine which Retailer Sold the Most Women's Athletic Footwear:** Created a filtered dataset with only Women's Athletic Footwear in the products column. Determined which retailers sold the most women's athletic footwear, breaking it down by region, state, and city and calculating the units sold sum.
6. **Determine the Day and Week with the Most Women's Athletic Footwear Sales:** Using the dataframe created in the previous step, I resampled the data to show the day and week with the highest sales. 

## Findings For Each Part 
1. No analysis, just cleanup and data prep. 
2. **Determined which Region Sold the Most Products:** The Northeast, Specifically in the city of New York with 111,954 products sold. The second region that sold the most products was the South, Texas. 
3. **Determine which Region had the Most Sales:** The Northeast, Specifically in the city of New York with 3,9801,235 total sales. The second region that sold the most products was the West in San Francisco, California. 
4. **Determine which Retailer had the Most Sales:** West Gear, in San Francisco, California	with 32,794,405 total sales. 
5. **Determine which Retailer Sold the Most Women's Athletic Footwear:** West Gear, in San Francisco, California sold the most Women's Athletic Footwear, with 12,107 Womens Footwear Units Sold. 
6. **Determine the Day and Week with the Most Women's Athletic Footwear Sales:** Across all regions, the date with the most sales was 2021-07-16. However, the week with the most sales was 2021-12-19, the week before Christmas. 

## Conclusion
This dataframe represents a combined set of data from 2020 and 2021 of Athletic Footwear and Apparel Sales for Men and Women. Looking through our findings it seems the West and The Northeast are frontrunners on having the most products sold and highest number of total sales. 
 