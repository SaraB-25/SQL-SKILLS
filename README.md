# SQL-SKILLS
## 📌 Project Overview
This project analyzes world database using SQL
## 🎯 Objectives
- The goal is to be able to explain basic SQL syntax
-  Understand how to implement data manipulation and filtering. 

## 📊 Tools & Technologies
-	SQL


## 🔍 Key Steps in Analysis
-Once imported the world database in to SQL ,we have been demonstrating several queries to    clean and manipulate the db. Below are examples of the tasks we did,
- Question 1.
Count Cities in USA
-Query used :  Select Count(Name) AS CitiesinUSA  from City  where CountryCode ='USA' ;

<img width="940" height="383" alt="image" src="https://github.com/user-attachments/assets/fad96399-3c51-48d2-949f-244b4db6e56b" />

###Question 2,
Country with Highest Life Expectancy
Query used :select Name , LifeExpectancy from Country order by LifeExpectancy DESC Limit 1 ;

<img width="940" height="483" alt="image" src="https://github.com/user-attachments/assets/25ecf540-c7f4-40a0-baa8-5e9fcddebfc5" />

###Question 3,
"New Year Promotion: Featuring Cities with 'New
Query used: select * from city where Name Like "%new%" ;

<img width="906" height="470" alt="image" src="https://github.com/user-attachments/assets/dd8a5162-e601-4503-a34b-aa7956d67952" />

###Question 4
Display Columns with Limit (First 10 Rows):
Query used: select Name, population from city order by Population desc limit 10

<img width="906" height="492" alt="image" src="https://github.com/user-attachments/assets/5ac25099-3ac1-4a65-b718-89acb101f5b1" />

### Question 5
Cities with Population Larger than 2,000,000
Query used: select * from city where Population > 2000000 ;

<img width="940" height="442" alt="image" src="https://github.com/user-attachments/assets/a6e645bb-1350-433e-a6e2-9468326a1b14" />

###Question 6.
Cities Beginning with 'Be' Prefix
Query used: select * from city where Name  like "Be%" ;

<img width="906" height="420" alt="image" src="https://github.com/user-attachments/assets/2b999d6b-f3da-4f97-8fdf-7aaebba7598e" />

### Question 7
Cities with Population Between 500,000-1,000,000
Query used: select * from city where Population between 500000 and 1000000 ;

<img width="906" height="428" alt="image" src="https://github.com/user-attachments/assets/e86e4424-772e-4227-a6ef-81d2333a53a2" />

### Question 8
Display Cities Sorted by Name in Ascending Order
Query used: select Name from city order by  Name ASC ;

<img width="906" height="477" alt="image" src="https://github.com/user-attachments/assets/3ca14a43-48d6-4b06-a18a-466e5f3e7fdc" />

###Question 9
Most Populated City
Query used: select Name, Population from city  order by Population Desc limit 1 ;

<img width="906" height="501" alt="image" src="https://github.com/user-attachments/assets/6dccca46-b4c0-4418-99fc-6e44112dbeb8" />

###Question 10
City Name Frequency Analysis: Supporting Geography Education
Query used:select Name ,count(*) AS Frequency from city  group by Name order by Name ASC ;

<img width="940" height="486" alt="image" src="https://github.com/user-attachments/assets/33bc06fc-7604-4ab0-a9a7-7373d3bb2649" />

## 📌 Results
- Became able to explain the SQL syntax
-  Understood data manipulation and filtering 












