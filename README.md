# DATA ANALYSIS for XYZ Company
Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.

The data folder contains datasets from three different branches; Lagos, Abuja and Port Harcourt. Each data file from the branches contains the same attribute information.

# Project Steps

To caery out the analysis, all the necessary and relevant libraries were imported on the jupiter Notebook using pandas. the libraries includes: numpy, pandas, seaborn, matplotlib. etc.
The XYZ company project was carried out in the following steps:

# Step 1 - Loading Datasets
-- Correct use of pathname pattern - glob
-- Combine all the files generated in a list and export to a CSV.

# Step 2 - Data Exploration
-- Use the head() method to view first few rows of the dataset
-- Check the number of rows and columns present in the data using the shape attribute.
-- Generate the names of the columns using the columns attribute.
-- Use describe function to generate the statistical summary of the dataframe
-- Use meaningful sentences to describe findings from the data statistical summary
-- Use of correct method to check for Missing values
-- Check the information of the DataFrame using the info method.

# Step 3 - Dealing with DateTime Features
-- Use to_datetime() to convert the date column to datetime
-- Check the datatype to confirm if it's in datetime
-- Accurate conversion of the time column & prints appropriate data type
-- Accurate extraction of the Day, Month, Year & Hour features
-- The numbers of unique hours of sales in the supermarket are accurately determined.
-- Result that shows an array that contains the unique sales hours.

# Step 4 - Unique Values in Columns
-- Appropriate method to generate the unique values in the categorical columns (apart from the example - Branch column).
-- Generated the count figure of the categorical values using the value_counts() method.

# Step 5 - Aggregation with GroupBy
-- A groupby object with the "City Column", and aggregation function of sum and mean.
-- A table that shows the gross income of each city, and determines the city with the highest total gross income.
-- Optional - Use of appropriate methods & descriptions to explore other columns such as Unit Price, Quantity.

# Step 6 - Data Visualization
-- Appropriate use of countplot to determine the branch with the highest sales record.
-- Optional - Appropriate use of countplot to determine the most used payment method & city with the most sales.
-- Appropriate use of countplot to determine the highest & lowest sold product line.
-- Result that shows the Payment channel used by most customers to pay for each product line. Chart should also show the "product line" column on the Y-axis, and the "hue" parameter for the "Payment" column. 


# Insights

Retrieving datasets from internet to working directory makes me understands more of the data analysis concept, data wrangling, grouping relevant columns, working with null values, also while analysing with visualization, i came across more types of visualization and more understanding of datetime functions.

# Future Work

one of the task that might be included in future work will be stretching on working with missing files, iterations, replacing strings. more works on visualizations like distplot(), swarmplot(), pointplot() and et al.

# Standout Section

The seaborn visualisation. analysing the data with the visualization makes the analysis easier and precise.



# Executive Summary.
[project executive-summary.docx](https://github.com/adesojinurudeen/Data-Analysis-Project/files/8200961/project.executive-summary.docx)
