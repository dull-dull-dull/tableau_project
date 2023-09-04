# Final-Project-Tableau

## Project/Goals

Present dashboard user with top listings and relevant market data for their search filters.

## Process
### Data cleaning (python)
### EDA - various visualizations used to assess general market trends, identify outliers and remove where necessary.
### Create dashboard from visualizations
### Format dashboard

## Results

Option 2: Airbnb

Data Question - Which listings provide the best value?

I navigated the prompts by making visualizations of number of listings, average price, average rating, and listing count for suggested categorical features and seeing when their combinations produced relevant insight. I first did this at the listing level where possible, but found more relevant insights by organizing data at the neighbourhood (and occasionally ZIP Code) level. I then compared datapoints, distributions, and trends in aggregated data and developed a dashboard. 

The dashboard allows its user to viisualize market data for the subsection of the listings relevant to them, filterable by listing price, neighbourhood, room type, number of beds, and/or ZIP code. 

The dashboard also provides a table containg information about the top relevant listings for the user filtered subsection of the data. This table shows listings with 10 or more reviews ordered by review score.

## Challenges 

Limited date/time data is an obstacle to forecast analyses – few years included in dataset due to company's limited history. Having only one metric of date/time data limited the number of trend analyses possible.

Dataset would ideally include or be paired with booking/rental data allowing for trend analyses including the number of bookings vs. the number of listings in each neighbourhood/zip code over time. This would help in forecasting growth and demand, which we could use in geo-targeting the allocation of advertising budgets to attract an appropriate number of hosts for each neighbourhood.

## Future Goals
I would attempt to draw in more data, particularly further information about hosts, bookings, and users if possible. 

I would use that data to further sort and filter top listings (e.g. resolving equivalent listing ratings by preferring the host with the highest overall rating, allowing the dashboard to be filtered by availability, etc.).

I would also assess how rating and price correlated with bookings and whether those correlations are consistent across neighbourhoods / time.
