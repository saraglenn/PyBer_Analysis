# PyBer_Analysis

## Overview 

The aim of this analysis was to create a summary of the ridesharing data by city type for a large dataset using Python. Pandas and Matplotlib were then used to create a multiple-line graph that demonstrates differentiation in the data by city type, as well as how those difference can be used in decision making by PyBer. 

## Results 

The summary of ridesharing data provides information on total rides, drives, and fares, as well as average fare per ride and average fare per driver by rural, suburban, and urban sectors. As one would expect, the urban areas had the highest number of total rides by as much as 92% in comparison to rural areas; the highest total of drivers by 390% compared to suburban areas and 2987% more than rural areas. Alternatively, due to the high volume, the urban areas had the lowest average fare per ride and lowest average fare per driver. 

![new_pyber_summary](https://github.com/saraglenn/PyBer_Analysis/assets/119461431/1d0f7e19-90f4-49a3-9309-acab7762a670)


In the following table the resmaple() function was used to parse the weeks and then apply the sum() method to get the total fares for each week. This gives us a view of how the rural, suburban, and urban locations compare from week to week. 

![resample](https://github.com/saraglenn/PyBer_Analysis/assets/119461431/d31f064e-15e5-494d-bd38-2156d68b1a38)

The multiple line graph was created using the object-oriented interface method and the df.plot() function, as well as matplotlib. This line graph provides a visualization of the trends in total fares by city type across four months. 

![total_fares_line_graph](https://github.com/saraglenn/PyBer_Analysis/assets/119461431/2b356c4b-ee1a-4fd5-8f4a-bb1be94f9409)

## Summary Recommendations

1. Focus on rural expansion: Although urban areas have higher demand and more drivers, there is significant untapped potential in rural areas. With only 8% of the total rides compared to urban areas, there is an opportunity to increase market share by expnding services and targeting rural customers. Implement marketing campaigns and incentives to attract both riders and drivers in rural areas. 
2. Improve driver compensation: Due to the high volume of drivers in urban areas, the average fare per driver is lower compared to suburban and rural areas. To attract and retrain quality drivers, consider impleemnting a tiered payment structure or driver incentives in urban areas to ensure drivers are fairly compensated. 
3. Target suburban markets: Suburban areas show a relatively high demand for ridesharing services, but the number of drivers is significantly lower compared to urban areas. Invest in expanding the driver network in suburban areas to bridge the gap between demand and supply. This can hep capture a larger market share in suburban regions and increase overall profitability. 

These recommendations aim to diversify the customer base, optimize driver compensation,a nd capitalize on untapped market potentialt o drive growth and profitability for the ridesharing company. 




