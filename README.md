# aditipendurkar.github.io

Project Review:
This project builds a data warehouse in SQLite from orders.csv and products.csv. It supports analytical queries and demonstrates how the model can be used for dashboarding.

Dependencies: Python, Sqlite, pandas

The data provided on the assignment was saved into a csv file and uploaded for use.


Schema:
**transactionsDetails** (FactSales): 
- salesKey, dateKey, productKey, quantity,unitPrice 
salesKey- Primary Key
dateKey- Foreign Key
productKey- Foreign Key 

**dataProduct** (DimProduct): 
- productKey, ProductID, ProductName, Category, Cost   
productKey- Primary Key
    

**dateDetails** (DimDetails) :
- dateKey, dateISO, Year, Month, Day
dateKey- Primary Key

