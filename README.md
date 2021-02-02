# Tableau-Homework

This homework/project works with data from the New York Citi Bike Program, https://en.wikipedia.org/wiki/Citi_Bike and uses Tableau Public. 
The analysis contained herin was performed on data from January 2018 thru May 2020 for the New Jersey stations only, https://www.citibikenyc.com/system-data .

The Tableau Public workbook includes the following.

	 11 "Phenomenon" Visualizations
	 
	 4 Dashboards (two of these are offical maps showing starting and ending stations in New Jersey)
	  
	 1 Story (describes detail about bike trips)
	 
Each page includes text/markdown with analysis on observations uncovered from the data.

## Getting Started
The ETL process was initiated within a Jupyter Notebook, CityBikeCSVcheck.ipynb.
This notebook used Pandas to clean the data and Glob to quickly load the CSV files and Pickeled the data to reduce the file size. 
The starting and ending bike station data was consolided since it was duplicated on each transaction. A separate table/file was created for the starting stations and ending stations. This left the transaction data with only a reference number to the particular station.

Within Tableau Public, the files were joined on the starting and ending station columns as a inner join. Analysis was performed on this loaded database.

### Prerequisites

This homework/project uses Tableau Public. This is the free tier of Tableau and only lets you save to their public server. You will need an account to view this workbook. Here is a link to get your free tier of Tableau.

https://public.tableau.com/s/

Here is the link to the completed workbook.
https://public.tableau.com/profile/randall.a.dettmer#!/vizhome/CitiBike_twbx/StartingActivity?publish=yes

### Files

[Raw data from Citi Bike (/Resources)](/Resources)

Screen Shots (folder) - screen shots of various visualizations from Tableau; many include observations and/or notes
[Screen Shots (/Screen_Shots)](/Screen_Shots)

CityBikeCSVcheck.ipynb - Jupyter Notebook file used to clean and organize data for Tableau Homework.  The files from CitiBike were very large and there were duplicate items in each data set.  Using the Jupyter Notebook, I was able to clean and reduce the data duplication.  For example, each transaction had compete starting and ending station information.  Reducing that to a code number and then using this code number as a reference, I was able to reduce the amount of data space required but also keeping the integrity of the information contained therein.
[Jupyter Notebook (CitiBikeCSVcheck.ipynb)](CitiBikeCSVcheck.ipynb)

bikedata2019A - January thru June 2019 data
[bikedata2019A - January thru June 2019 data (bikedata2019A.csv)](bikedata2019A.csv)

bikedata2019B - July thru December 2019 data
[bikedata2019B - July thru December 2019 data (bikedata2019B.csv)](bikedata2019B.csv)

bikedata2020 - January thru May 2020 data
[bikedata2020 - January thru May 2020 data (bikedata2020.csv)](bikedata22020.csv)

endstation - Ending station data
[endstation - Ending station data (endstation.csv)](endstation.csv)

startstation - Starting station data
[startstation - Starting station data (startstation.csv)](startstation.csv)

## Versioning

This homework/project uses Tableau Public version 2020.3.

The Jupyter Notebook used Python 3.

## Acknowledgements



