# Project Title


Analysis of Company XYZ Supermarket data across the Country.


# Project Steps


STEP 1: Loading the datasets - The company has 3 branches which means, working with 3 datasets as well. Here, the datasets were combined into one making use of the glob library to read them from the working directory, concatenated using Pandas and saved as a csv file for better analysis.

STEP 2: Data Exploration - exploring the loaded dataset using some built-in Pandas function. Inspecting the first 5 rows of the data, knowing the total rows and columns present, exploring the statistical summary, checking for missing values and the concise summary information of the dataframe which includes the column datatypes, memory usage etc.

STEP 3: Dealing with DateTime Features - From the summary exploration, the columns were in their correct datatype format except the date and time columns which are in object datatype instead of datetime. These columns are being converted to the datetime datatype and confirmed. Also, new Features such as day, year, month, hour were extracted from those 2 features. The numbers of unique hours of sales in the supermarket are accurately determined and result that shows an array that contains the unique sales hours printed.

STEP 4: Unique Values in Columns - A list of the categorical column in the dataset is derived by iterating through the columns to check if each element is an object datatype. then, generate the unique values in the categorical columns and its value counts.

STEP 5: Aggregation with GroupBy - Create a groupby object to display a table that shows the gross income of each city, and determine the city with the highest total Gross income,Unit price and Quantity.

STEP 6: Data Visualization - Answers to some questions such as 
-the branch with the highest sales record, 
-most used payment method, 
-the highest & lowest sold product line, 
-branch with the highest and lowest customer rating, 
-payment channel used by most customer to pay for each product line,
-interaction of Unit price on the Quantity of goods purchased etc by generating charts using the seaborn library and making use of different plotting styles for brtter understanding. 


# Insights


1. Data is cleaned, no outlier or missing value
2. Branch A sees the most number of orders and owns the highest sales record
3. By a difference of 1 between Electronic and Cash mode of payment; Epay has the highest count while card payment has the least
4. The supermarket location with the most sales is Lagos
5. The most common customers are the Member type - Returning customer with membership card
6. The Female gender are seen to be the most patronizing customers by a difference of 2 with respect to the Male gender
7. Fashion accesories is the highest sold Product line, followed by Food and beverages while Health and beauty is the least
8. Electronic accessories are mostly paid in cash with over 70 in count than other product line
9. In branch C, the most common mode of payment is in cash while branch A and B is the Epay
10. Port Harcourt generates a gross income greater than that of Abuja and Lagos
11. Epay is the most used form of payment transaction


# Future Work


Increase the dataset with more transactions over the months so as to better understand sales trends, making this project more robust and determine its growth. Also, Build a model to predict/forecast for future sales.


# Standout Section


Defined a function to give the count and percentage of missing values, generated more visuals to explore and uncover insights  such as: the total number of orders for different branch, the number of products purchased by customer(by gender) per day, the cost of goods sold by each city, rating by each gender and their payment method, the month and city with the highest gross income across the branches for the 3 months. Giving detailed approach and summary of each step making use of inline comments and markdowns.


# Executive Summary.


The executive summary of this project for company XYZ above explains processes and insights uncovered that can help the company.
