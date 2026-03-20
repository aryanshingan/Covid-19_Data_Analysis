# Covid-19_Data_Analysis
This project analyzes global COVID-19 data using the Johns Hopkins University dataset. It involves data collection, cleaning, preprocessing, and exploratory data analysis to identify infection trends, recovery rates, and high-risk regions. 

# Objecctive 

Analyze COVID-19 data to track infection trends, recovery rates, and identify high-risk regions.

# Dataset


Johns Hopkins University COVID-19 Dataset (Global data)
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series

# Project Steps

-Data Collection: Imported global COVID-19 case data from multiple sources.
-Data Preprocessing: Cleaned data, filled missing values, and formatted date columns for time series analysis.
-Exploratory Data Analysis (EDA): Visualized infection and recovery trends using line charts and heatmaps.
-Feature Selection: Focused on population density and testing rates to analyze impact on case numbers.
-Insights: Identified regional trends, growth patterns, and most affected areas.

# Code Cell Description

Cell 1: Imported required Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.
Cell 2: Loaded the COVID-19 dataset from Johns Hopkins data repository.
Cell 3: Displayed dataset overview using head() and info() for initial understanding.
Cell 4: Cleaned missing values and standardized date/time formats.
Cell 5: Filtered and grouped data for daily case trends by country.
Cell 6: Created line plots showing global case growth over time.
Cell 7: Generated heatmaps highlighting most affected countries.
Cell 8: Performed correlation analysis between infection rates and population/testing.
Cell 9: Summarized findings and insights from EDA.

# Tools Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
Google Colab for implementation

# Conclusion

The analysis provides insights into infection spread, aiding better health policy decisions and pandemic response strategies.
