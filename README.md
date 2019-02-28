# GW_Project2_ETL:

Step 1 – Extract:
  * Download CSV files from Open Data DC for parking and moving violations in DC for each month in 2018
  * Download CSV file from Open Weather Map for weather data in DC in 2018
  
Step 2 - Transform:
  * Combine monthly data for parking and moving violations in DC into respective Data Frames
  * Re-create Data Frames for parking and moving violations in DC to feature columns of interest, and re-index each Data Frame    on date
  * Import data from Open Weather Map into Data Frame, and clean data:
  * Convert ‘Weather ID’ column into numerical precipitation data based on information from e-mail to Open Weather Map
  * Re-index Data Frame on date
  * Join parking violations Data Frame and weather Data Frame, and moving violations Data Frame and weather Data Frame on date
  * Use Pandas library to count the number of parking and moving violations on a specific date
  * Create new Data Frame with date as index, and number of parking and moving violations on that date
  * Create plots to show relationships between weather and parking and moving violations

Step 3 - Load:
  * Use SQLAlchemy to load data frames into AWS and local MySQL server

