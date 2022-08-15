# Surfs Up
Performing analysis on Hawaii temperatures to uncover seasonal trends.
## Overview of Project
This weeks challenge helps us build upon our skills learned in this weeks module. For deliverables, the client wanted additional information analyzed about temperature trends before opening the surf shop. Temperature data for the months of June and December in Oahu were investigated in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results
The analysis had few tasks. For Deliverable 1 and Deliverable 2 Using Python, Pandas functions and methods, and SQLAlchemy, date data was filtered from the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Then each month's tepmerature were convereted to a list and dataframe to generate the summary statistics.

### June Temperature Summary Statistics
![june_temps](https://user-images.githubusercontent.com/107658895/184564290-11f934c2-86f1-44c6-9b69-5bc9eec5b2f8.png)
##### Figure 1: Displays the temperature summary statistics for the month of December
* Average Temperature
  * 74.94F
* Minimum Temperature 
  * 64F
* Maximum Temperature
  * 85F
* Standard Deviation
  * (+/-) 3.26F


### December Temperature Summary Statistics
![december_temps](https://user-images.githubusercontent.com/107658895/184564409-3733e5e9-ecc5-42b7-9dbc-f189a45bd505.png)
##### Figure 2: Displays the temperature summary statistics for the month of December
* Average Temperature
  * 71.04F
* Minimum Temperature 
  * 56F
* Maximum Temperature
  * 83F
* Standard Deviation
  * (+/-) 3.75F


## Summary
Based on the summary statistic results for two months, it's seen that on average, temperatures are sustainanle enough to start a surf and ice cream shop business year-round. Other paramaters, such as tidal activity or tourist activity per island, can be a important parameters to further investigate whether a surf shop is sustainable year round. It'll give valuable information if people surf in the cold months and in which Hawaii island. Finally another query should be made for each winter month of Hawaii. It was just assumed that December was the coldest month. After further investigation for the month of january it was found that it was a much colder difference than June to December.

![january_temps](https://user-images.githubusercontent.com/107658895/184568211-cb3e7270-00d1-400e-b9c6-d3a3aa80124d.png)
