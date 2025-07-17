# hotel_bookings
A project completed for my Level 4 Data Analyst Apprenticeship Communicating Insights Residential. 

The data is open source and found here: [Hotel Bookings Dataset](https://www.kaggle.com/datasets/mojtaba142/hotel-booking)

1. Data cleaning was done in Excel, with some analysis done in both Excel and Python.
  - Created a unique identifier column for rows to aid in potential tracking and outlier
analysis.<br>
  - Created a derived arrival date column and standardized month, day, and year data
types.<br>
  - Ensured variables in text columns (e.g. reservation status column) were consistent;
addressed spelling variations.<br>
  - Replaced null values in Agent and Company fields with ”No Agent” and ”No Company.”
  - Created a total stay duration column by summing weekday and weekend night stays
columns.<br>
  - Removed outliers: some ADRs were 0 and these were filtered out during investigation of optimal length of stay for best average daily rate.
2. Random Forest predictive modelling requires further development, testing and evaluation, due to the short timeframe the project demanded. 

