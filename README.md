# SALES ANALYSIS

In this project I use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. 
The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

## I started by cleaning the data.

- Drop NaN values from DataFrame.
- Removing rows based on a condition.
- Change the type of columns (to_numeric, to_datetime, astype)

### Once I have cleaned up the data a bit, I moved into the data exploration section. In this section I explore 5 high level business questions related to this data:

1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

### To answer these questions I walked through many different pandas & matplotlib methods. They include:

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
