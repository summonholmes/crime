# Orris J. Disney II
# Python/SQL Project for Spring 2019

# Violent Crime and Police Officer report

 -- United States Population Count Over The Years 

 -- Violent Crimes Counts Compared to Police Officers Count Over the Years

This project was an attempt to answer the following question:

  "Does the number of violent crimes rise or fall depending on the number of police officers in United States?"

## The data gathered for this project is the yearly count for the following items:

  a. Population
  
  b. Violent Crimes
  
  c. Police Officers
      
## 1. The following steps of this project:

  a.  Download/create the two csv files:
  
    - Population and Violent Crimes is from one location
    
    - Number of Police Officers is from another location
    
  b.  Create a database only if it doesn't already exist, or connect to the database if it already exists.   The name of the database is violentcrimes.db.   It's created in the same folder as the python program and the three CSV files.
  
  c.  In the SQLite database, import the data from two of the csv files into two different tables:
  
      - If the tables already exist, they will be deleted to prevent importing duplicate csv files into the same table
      
      - Once the table is created, the data will be imported
  
  d. Once the import is completed, a printout of the data in the two tables is displayed.  The printout will confirm that the data was correctly imported from the CSV file to the sqlite database tables.
  
  e.  Create a query that links the two tables.   I use the year data column to link both tables.   
  
  f.  Data results are graphed using matplotlib.
  
## 2. Dependencies:

  a. sqlite3
  
  b. csv
  
  c. matplotlib.pyplot
  
  d. pandas

## 3. Make sure the following files are in the same folder:

  a.  yearlycrime.ipynb

  b.  population_and_violent_crime_97_2016.csv
  
  c.  number_of_peace_officers_table.csv
  
  
Please reach out to me if you've found any issues or have any questions.  

Thanks.


References:

1. Count of Police Officers
  https://www.bjs.gov/content/pub/pdf/nsleed.pdf
  The table with title "Number and rate of full-time officers reported to the UCR, by sworn status, 1992–2012"
  Note about the data: There were three different tables of data but I only focused on the UCR data.
  
  The FBI collects data on the number and type of law enforcement employees as part of its Uniform Crime Reporting (UCR) Program.

2. Population and Violent Crimes Count - 
  https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/topic-pages/tables/table-1

