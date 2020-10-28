# Tableau-Homework

This homework/project works with data from the New York Citi Bike Program, https://en.wikipedia.org/wiki/Citi_Bike and uses Tableau Public. 
The analysis contained herin was performed on data from January 2018 thru May 2020 for the New Jersey stations only, https://www.citibikenyc.com/system-data .

The Tableau Public workbook includes the following.
	 9 "Phenomenon" Visualizations
	 2 Dashboards
	 1 City Offical Map
	 1 Story
Each page includes text/markdown with analysis on observations uncovered from the data.

## Getting Started
The ETL process was initiated within a Jupyter Notebook, CityBikeCSVcheck.ipynb.
This notebook used Pandas to clean the data and Glob to quickly load the CSV files and Pickeled the data to reduce the file size. 
The starting and ending bike station data was consolided since it was duplicated on each transaction. A separate table/file was created for the starting stations and ending stations. This left the transaction data with only a reference number to the particular station.

Within Tableau Public, the files were joined on the starting and ending station columns as a xxx join. Analysis was performed on this database.

### Prerequisites

This homework/project uses Tableau Public. This is the free tier of Tableau and only lets you save to their public server. You will need an account to view this workbook. Here is a link to get your free tier of Tableau.

https://public.tableau.com/s/

Here is the link to the completed workbook.
https://public.tableau.com/profile/randall.a.dettmer#!/vizhome/CitiBike_twbx/StartingActivity?publish=yes

### Files

Resources (folder) - raw data from Citi Bike
Screen Shots (folder) - screen shots of various visualizations from Tableau; many include observations and/or notes

CityBikeCSVcheck.ipynb - Jupyter Notebook file used to clean and organize data for Tableau Homework.
bikedata2019A - January thru June 2019 data
bikedata2019B - July thru December 2019 data
bikedata2020 - January thru May 2020 data
endstation - Ending station data
startstation - Starting station data

## Versioning

This homework/project uses Tableau Public version 2020.3.
The Jupyter Notebook used Python 3.

## Acknowledgements



