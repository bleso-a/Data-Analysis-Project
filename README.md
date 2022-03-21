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
-- Appropriate use of countplot to determine the most used payment method & city with the most sales.
-- Appropriate use of countplot to determine the highest & lowest sold product line.
-- Result that shows the Payment channel used by most customers to pay for each product line. Chart should also show the "product line" column on the Y-axis, and the "hue" parameter for the "Payment" column. 


# Insights
during data wrangling i was ab le to have clearer picture of some functions in data analysis, which are very vital when it comes to analysis. some of it are the visualization, null value, unique value, Mean and standard deviation as listed below.

  # 1. Visualisation
    this  visualising the data helps in decision-making, helps to inerrelate the data to find better insights and reap the importance of data visualization in analyzing the data in a beter way. it helps the business stakeholders focus on the areas that requires attention. it helps in fast decision making. this is because human process visual better than any tedius tabular forms or reports. it means if the data communicates well, decsion-makers can quickly take actions based on the new data insights.
    
   # 2. Unique()-value:
   this function is used to find the unique elements of an array. it returns the sorted unique elements of an array.
   
   # 3. Mean() function:
    this is an important measure in the data analysis that plays vital roles in the decision making. Because it gives us an idea of where the center value is located in a dataset. it incoperates the score from every values of rows in columns of the datasets. which will count the total value of rows in the columns, add up all the values and divide by the total number of values in tthe columns of the dataset. 
    
   # 4. Null-value:
   A NULL value is a special marker used in data analysis to indicate that a data value does not exist  in the datasets. its a placeholder to denote values that are missing or that we do not know.
   # 5. Groupby() 
   groupby is used for grouping data according to the categories and apply a function to the categories. it also helps to aggregiate data efficiently during data analysis. it also helps to get an overview of the dataset. it makes it easier to explore the dataset and unveil the underline relationships among variables.
   
# Future Work
one of the task that might be included in future work will be stretching on working with missing files, iterations, replacing strings. more works on visualizations like distplot(), swarmplot(), pointplot() and et al.

# Standout Section
since data visualization is vital part of data analysis. more seaborn functions was used to visualize dataset baseon their variance. for example:
  sns.catplot(x='Product line',y='Quantity', Units='product line per Quantity', data=df, aspect=4, kind='point')
  
  catplots was used to visualise the analysis in product line and quantity: that is product line per quantity.
  
  sns.boxplot(x='Branch', y='gross income', data=df).set_title("Sales Records")
also Boxplot also used to visualise the analysis of gross income per branch.

  sns.countplot(x='Payment', hue='Branch', data=df).set_title("Sales Records")
countplot also used to visualise the analysis of payment method most used in branches


# Executive Summary.
