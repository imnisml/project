# Project on Supermarket Sales Analysis 

by **Noor Iman Ismail** (imnisml)

This project is to analyze the growth of supermarket with multiple branches in the most populated cities. Using Pandas in Python library for exploratory data analysis (EDA), the data are able to be investigated, analyzed, and cleaned accordingly. 


The objectives of this project are to:
 - Identify the dataset
 - Calculate the supermarket cost of goods sold, gross margin, and gross income
 - Analyze and visualize the supermarket's gross income
 - Search data base for user input

## About the Dataset

Supermarket_Sales dataset is obtained from [Supermarket Sales by Aung Pyae](https://www.kaggle.com/aungpyaeap/supermarket-sales). 

The data dictionary attribute information of the fields (columns):

- **Invoice ID** - Computer generated sales slip invoice identification number.
- **Branch** - Branch of supercenter identified as A, B, and C.
- **City** - Location of supercenters.
- **Customer** - Type of customers, recorded by Members for customer using member card and Normal for without member card.
- **Gender** - Gender type of customer.
- **Product line** - General item categorization groups.
- **Unit price** - Price of each product in Dollar.
- **Quantity** - Number of products purchased by customer.
- **Date** - Date of purchase.
- **Time** - Purchase time.
- **Payment** - Payment used by customer for purchase
- **Rating** - Customer stratification rating on their overall shopping experience (on scale of 1 to 10).


#### 1. Dataset identification

To observe the available dataset.

- Import `Pandas`, `NumPy`, and `matplotlib.pyplot`
- Read the `.csv` file and assign to a variable
- Observe the first five rows
- Set the index of the dataframe
- Observe the number of rows and columns of the dataset
- Identify the information of the dataframe
- Identify the missing data
- Identify the data type of each column



#### 2. Cost calculation

To calculate the cost of goods sold, total price, gross margin (%), and gross income of the supermarket.

- Change the data type of `Unit price` from object to float
- Create a class function of cost calculation
- Calculate the cost by assigning to class function and designated define functions



#### 3. Analyze and visualize calculated data

To analyze the calculated data, `Gross income` based on several specified data.

3.1 Statistical approach
- Calculate the statistic data of `Gross income`
- Plot a box chart using `Gross income` statistic data

3.2 Relationship between product value, sold item, and gross income
- Observe the effect of product value and sold item on the `Gross income`

3.3 Relationship between `Gross income` and `Location`
 - Sum the value of `Gross income` according to the `City`
 - Plot a bar chart between `Gross income` and `City`
 
 3.4 Relationship between `Gross income` and `Date`
 - Change data type of `Date` to datetime format
 - Create a copy of dataframe containing data of `Date` and `Gross income`
 - Create a new column `Day` containing data of 'day of year' using `Date`
 - Sum the `Gross income` according to 'day of year'
 - Plot a line graph observing data of `Day` and sum of `Gross income` per day
 
 
 
 #### 4. Search data base for user input
 
 To enable user to search data base according to categories.
 
 Category: Invoice Number, Branch Location, Payment Type
 
 - Create several user define functions for each category
 - User input with try/excerpt block

## Thank You!
