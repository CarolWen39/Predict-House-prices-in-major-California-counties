Our data cleaning strategy is to organize data by months, using pandas dataframe.

## Data Summary
After processing the data as we mentioned above, we got a dataset which contains 7344 items from Jan, 2010 to Dec, 2021. We have 8 features shown below.
We only selected 10 popular counties’ data from our dataset.


| Feature | Description |
| --- | --- |
| Date | Monthly from Jan, 2020 to Dec, 2021 |
| County | 51 major counties in CA, including LA, SF, etc |
| Ozone | Average Ozone value of each month in corresponding county, missing value is setted as average of all counties |
| PM2.5 | Average PM2.5 value of each month in corresponding county, missing value is setted as average of all counties |
| Water Conductance | Average Water Conductance value of each month in corresponding county, missing value is setted as average of all counties |
| Water PH | Average Water PH value of each month in corresponding county, missing value is setted as average of all counties |
| Oil Fields | Counts of oil fields of each month in corresponding county, default as 0 |
| Gas Well | Counts of Gas Well of each month in corresponding county, default as 0 |
| Covid positive test cases | Represents the positive Covid testing cases from Mar, 2020 in California; before is default as 0 |
| Fire | Counts of fire appear in the cetain month

