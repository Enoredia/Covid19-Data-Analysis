# Project Name: Covid19-Data-Analysis

--------------

# Project Objective

The coronavirus disease is a communicable respiratory disease caused by a virus that causes illness. The main objective of this project is to get insights from the data set to understand how this virus had impacted the world. I have carried out analysis to  understand the Total Confirmed cases, Total Recoveries and Total Death Cases.

--------------

# Data Sourcing
This dataset is updated daily and in a time-series format. It is a trusted dataset uploaded by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. it is contained in this link https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data. 

--------------

# Data Transformation
The data was scrapped using the web link (url) for cleaning and transformation with Power Query in Microsoft Excel. Microsoft Excel is used for this project.
This was done to clean and analyse the data:

-Loading of the Confirmed, death and recovery cases into the excel sheet.

-Editing the "source" tab so that we can remove the columns and enable real time updates

-The first rows were made to be headers of the table for accurate readability

-changed the data format from wide data to long data by unpivoting the date columns

-added new columns and named them appropriately with the first as recovered, confirmed and death respectively

-merged the three tables (confirmed, recovery and death) into one and then changed the format of the date column to be date format, the Recovered, Death and Confirm Columns were also changed from text format to number formats

-extracted day, month and year from the Date column into their different columns

-visualised with pivot tables and pivot charts

---------------

# Finding and Recommendations
-United States has the Highest prevalence of COVID-19 

-North Korea has the lowest prevalence case of COVID-19 

-Cummulative Monthly confirmed cases of COVID-19, June has the highest cases while 2022 has experienced an increase in the number of cases

It is important to maintain sanitary practices everyday.
