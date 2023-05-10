# Hotel Revenue
## Objective 
  Build a visual data story or dashboard using Power BI to present to the stakeholder
### Questions:
  - Is out Hotel revenue growing by year?
  - Should we increase our parking lot size?
  - What trends can we see in the data?
### Is our Hotel revenue growing by year?
We have 2 hotel types so it would be good to segment revenue by hotel type </br>
We do not have a revenue column so we have to calculate the revenue by using the adr (average daily rate) </br>
revenue = ([stays_in_weekend_nights] + [stays_in_week_nights])*([adr]*(1-[Discounts]) </br>
  - From the data, revenue for the hotel is increasing
  - The year 2020 is incomplete, it only goes till May 
### Should we increase our parking lot size?
We want to understand if there is a trend for guest with personal cars. 
  - From the data, we do not see a very high usage for personal cars. So increaseing parking lot size is unecessary. 
### What trends can we see in the data?
Focus on average daily rate and guest to explore seasonality
