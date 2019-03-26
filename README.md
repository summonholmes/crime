# Orris J. Disney II
# Python/SQL project for spring 2019

# Violent Crime and Police Officer report

 -- United States Population count over the years 

 -- Violent Crimes counts compared to Police Officers count over the years

This project was to try to answer the following question:

  "Does the number of violent crimes rises or fall depending on the number of police officers in United States?"

## The data gathered for this project is the yearly count for the following item:

  a. Population
  
  b. Violent Crimes
  
  c. Police Officers
      
## 1. The following steps that this project take when it is executed:

  a.  Download/create the two csv files
  
    - Population and Violent Crimes is from one location
    
    - Number of Police Officers from another location
    
  b.  Create a database only if it is not already created or connect to the database if it is already existed.   The name of the database is violentcrimes.db.   It will be created in the same folder where the python program and the three CSV files are located.
  
  c.  Import the data from two csv files into two different tables in the sqlite database
  
      - It will first delete the tables if it existed (to help prevent imported duplicate csv files to the same table)
      
      - Once the table is created, the data will then be imported
  
  d. Once the import is completed, a printout of the data in the two tables is displayed to confirm that the data was imported from the CSV file to the table in the sqlite database.
  
  e.  Created a query that linked between the two tables.   I will use the year data column to link both of the tables.   
  
  f.  Used matplotlib to graph my data results
  
## 2. You will need the following modules to run the program

  a. sqlite3
  
  b. csv
  
  c. matplotlib.pyplot
  
  d. panda 

## 3.   make sure you have the following files in the same folder

  a.  yearlycrime.ipynb

  b.  population_and_violent_crime_97_2016.csv
  
  c.  number_of_peace_officers_table.csv
  
  
Please reach out to me if you found any issues or have any questions.  

Thanks.


References:

1. Count of Police Officers
  https://www.bjs.gov/content/pub/pdf/nsleed.pdf
  The table with title "Number and rate of full-time officers reported to the UCR, by sworn status, 1992–2012"
  Note about the data: There were three different table of data but I only focused on the UCR data.
  
  The FBI collects data on the number and type of law enforcement employees as part of its Uniform Crime Reporting (UCR) Program.

2. Population and Violent Crimes Count - 
  https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/topic-pages/tables/table-1

