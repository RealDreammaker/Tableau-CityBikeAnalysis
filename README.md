# Citi Bike Analytics

## Background

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilisation. Through the team's efforts, each month bike data is collected, organised, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, my task is to build a set of data reports to provide the answers.

## Completed Tasks 

* Using python, [cleaned](Clean_csvfiles.ipynb) data files to unified format and then [merged](Concat_csv_files.ipynb) them 
* Selected date range from January 2019 to December 2020
* Used Tableau to produce results

## Results:

* [Tableau story](https://public.tableau.com/app/profile/hung.quoc.nguyen/viz/CityBike_16489037050090/Story?publish=yes)
* [twbx file](CityBike.twbx) (this file can also be download from Tableau Public website from the above link)

## Analysis on the phenomenons uncovered from the data

* From the start of Covid pandemic in US, bike trips dropped significantly. 
* The proportion of Short-term customers increase dramatically at the start of pandemic.
* Bikes are mostly used by mid age group (30-40) and male riders take about two third the proportion
* Given bike usage history (miles and hours ridden), some bike should be replaced or long due for service.
* People rides more during the day on weekends and more during peak hours on weekdays
* Stations with high usage might require more maintenance and expansion
* Before the start of Covid pandemic, riders likely use stations at central district and the annual subscribers take about 85%. 
* When the pandemic starts, riders started to spread out to stations further away from centre and number of short-term customers increased to nearly 50%.
