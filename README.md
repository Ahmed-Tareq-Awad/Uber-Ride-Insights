# Uber ride Insight 

*" This project analyzes one year of Uber ride data using Power BI to uncover usage patterns and actionable business insights. The dashboard offers a dynamic view of trip behavior by time, purpose, category, and seasonality. "*

# Analysis Steps :

---> Loaded the dataset into Power Query Editor for preprocessing 

---> Generated summary statistics to understand key metrics 

 ---> Data Cleaning & Transformation :-

- Handled missing values in the "Purpose" column using logical imputations 

- Removed duplicate records .

- Converted and standardized 'Start Date' and 'End Date' columns 

- Extracted time features (hour and minute) from datetime columns 

- Converted miles to kilometers to calculate trip duration 

- Added a new "Speed" column to evaluate average trip speed 

- Adjusted data types for consistency, ( Speed,Duration)

# Highlight & Key insight :

---> Peak Usage Time : Afternoon rides were most frequent; night rides were the lowest 

---> Seasonal Trends : October and March saw the highest total miles; January and September the lowest 

---> Ride Volume By Month : December and August were the busiest months, while May had the fewest rides 

---> Ride Purpose : Most rides were business-related (93%), followed by meals, entertainment, and temporary stays 

---> Ride Category : Business: 93% & Personal: 7%

---> Peak Day : Friday had the highest ride volume, indicating a surge at the end of the work week 

# Recommendation :

---> Align driver availability with peak demand times (afternoons, Fridays)

---> Offer promotions during low-demand months ( May & January)

---> Expand service capacity in months with consistent business travel (December & August)

---> Implement a feedback system focused on high-frequency purposes (meetings)

---> Encourage personal ride usage through targeted incentives 

