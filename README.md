# Tableau--New-York-City-Bike-Analysis


Tableau_New York CitiBike File documenting work: Homework-CitiBike.xlsx File documenting cleaning work: CitiBike.ipynb Link to Tableau data: https://public.tableau.com/views/NYC-BikeRide/Sheet5?:embed=y&:display_count=yes&:origin=viz_share_link

The cleansed data files as well as the raw data used could not be pushed to repository due to size.

Files Used:

Daily data: 201701-citibike-tripdata.csv 201705-citibike-tripdata.csv 201707-citibike-tripdata.csv 201711-citibike-tripdata.csv

Process to report:

The daily data contained only one month snap shots across each of the seasons so that comparisons could be made. The daily data needed to be cleansed of erroneous data such as: removal of all customers whose date of birth documented puts them over the age of 100. Since it is possible people aged 100 could ride, they were left in, however the volume of them I believe is still false. The daily data also needed to be cleansed of trips over four hours, since these are most likely the result of faulty returns or abandoned bikes or potential theft. The model for renting a bike, keeps the cost effective rental at 30 minutes, therefore, the likelyhood of trips over four hours is extremely small. Once most of the data was cleaned of obvious erroneous data and evaluated for some simple stats, smaller sections of the data was created for import into tableau. All the reports focus on grouped areas of interest: Customer / ridership information, equipment / bike information, trip information, customer detail comparsions, and station mapping details.
