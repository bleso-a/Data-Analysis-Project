NB: This is a template to make documentation process easy. You can remove the `To-Do` notes in your final commit

-Project Title
Analyze Supermarket Data Across the Country - Company XYZ

-Short Description of About the Company 
Company XYZ owns a supermarket chain across the country. Each major branch located
in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and 
determine its growth, as the rise of supermarkets competition is seen to increase.

There are 3 data folder available, each folder contain datasets from three different branches; Lagos, Abuja and Port Harcourt. 
Each data file from the branches contains the same attribute information. 

-Project Steps
Step 1 
- Loading Datasets
- Correct use of pathname pattern - glob
- Combine all the files generated in a list and export to a CSV.

Step 2 - Data Exploration
- Use the head() method to view first few rows of the dataset
- Check the number of rows and columns present in the data using the shape attribute.
- Generate the names of the columns using the columns attribute.
- Use describe function to generate the statistical summary of the dataframe
- Use meaningful sentences to describe findings from the data statistical summary
- Use of correct method to check for Missing values
- Check the information of the DataFrame using the info method.

Step 3 - Dealing with DateTime Features
- Use to_datetime() to convert the date column to datetime
- Check the datatype to confirm if it's in datetime
- Accurate conversion of the time column & prints appropriate data type
- Accurate extraction of the Day, Month, Year & Hour features
- The numbers of unique hours of sales in the supermarket are accurately determined.
- Result that shows an array that contains the unique sales hours.

Step 4 - Unique Values in Columns
- Appropriate method to generate the unique values in the categorical columns (apart from the example - Branch column).
- Generated the count figure of the categorical values using the value_counts() method.
- Drop the unnecessary column  using the drop attribute


Step 5 - Aggregation with GroupBy
- A groupby object with the "City Column", and aggregation function of sum and mean.
- A table that shows the gross income of each city, and determines the city with the highest total gross income.
- Use of appropriate methods & descriptions to explore other columns such as Unit Price, Quantity.

Step 6 - Data Visualization
- Appropriate use of barplot to determine the branch with the highest sales record.
- Appropriate use of countplot & barplot to determine the most used payment method & city with the most sales.
- Appropriate use of countplot to determine the highest & lowest sold product line.
- Result that shows the Payment channel used by most customers to pay for each product line. Chart should also show 
the "product line" column on the Y-axis, and the "hue" parameter for the "Payment" column. 

Step 7 - Time Series
- Loading Datasets again set the parse_dates to Dtae column and index_col to Date
- use the head() method to view the few rows of the dataset
- drop the unnecessary columns from the dataset
- Use the index attribute the check the index
- Use resample method on Total column and calculate the mean to view the Monthly frequency , Weekly frequency  
  and Business day frequency sales

# Insights

Explain the insights you were able to uncover from the analysing the datasets.
- Lagos city has the highest Gross income, Unit price and Quantity
- Branch C (Port harcourt) has the highest sales record with female has the highest purchase
- Epay payment has the highest payment method
- The highest sold product is Sport & Product and the lowest sold product is Health & Beauty
- Branch B(Abuja) has the lowest rating
- Sports and travel product has the highest Unit price while Electronic acessories has the lowest Unit price
- Fashion accessories has the lowest quantity and Home & lifestyle has the highest quantity Product
- Average Highest sales was made in the month of January while the average lowest  sales was made in March
- Total Highest sales was made in the month of January while the  total lowest  sales was made in February

# Future Work

Suggest tasks you might include in future work to make this project more robust.
If i have access to more data in the future, i would do more exploration and make use of statsmodels
and deccomposition method to find the trend, seasonality, residual of sales and many more

# Standout Section
Using Time Series to discover the weekly sales frequency and monthly sales frequency

# Executive Summary.

To-Do - Include your Executive Summary document in your repository.
