# Booking Calendar
![](https://badges.aleen42.com/src/python.svg)

---

## Tools

| Python  | SQL  | Enviroment
|---|---|----
Pandas|Postgresql| Jupyter Notebook
Psycopg2 | | DBeaver
## Description

The main purpose of this project is to extract the contents of the spreadsheets into a SQL database and create a new calendar table, with the number of properties available on a given date.

The logic follows these steps:
1. Set up the environment and variables;
2. Create the tables if they haven't been created before;  
3. Prepare and load the data into the database;  
3.1. Create a temporary calendar table with all the dates and ids of the busy apartments;
4.  Get the total** of apartments and subtract the busy apartments according to the date.  


>[NOTE]
   >
   > The total number of apartments considered was the total of unique ids contained in the both tables
   >  

   ----

   [@msoares-prog](https://github.com/msoares-prog)