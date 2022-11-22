# Blog Post: Emergency Calls
This project analyzes call data to the Seattle Police Department call center, and was
provided by the city of Seattle.

The most recent data can be accessed [here.](https://data.seattle.gov/Public-Safety/Call-Data/33kz-ixgy)

## Table of Contents
- [Libraries Used](#libraries-used)
- [Project Motivation](#project-motivation)
- [File Descriptions](#file-descriptions)
- [Blog Post Functions](#blog-post-functions)
- [Summary of the Analysis](#summary-of-the-analysis)


## Libaries Used
"Standard" data analysis libraries were used:
- NumPy
- Pandas
- Matplotlib
- Sklearn

Specific to Jupyter Notebooks:
- ipynb

[Table of Contents](#table-of-contents)


## Project Motivation
With such a massive amount of well-maintained information available, this provided an opportunity
to dive into what goes on when a police assistance call is placed. Specifically, we looked at:

1. What times were the majority of the calls placed? Are there any surges by
day of the month, or month of the year?
2. Do the amount of calls change by Precinct, Sector or Beat?
3. Does the Priority of calls change by Precinct, Sector or Beat?
4. The Computer Aided Dispatch (CAD) system assigns Priority. Can we create a model which
accurately predicts Priority?

[Table of Contents](#table-of-contents)


## File Descriptions
Jupyter Notebooks

Included in this repository are 2 Jupyter notebooks which assist in the exploration of this data.
They both have markdown cells to guide through the exploratory process.
1. blog_post_functions: separate from the exploratory notebook, this notebook contains the functions
created for assistance in the analysis.
2. blog_post_notebook: the exploratory analysis of the data.


CSV File

There is a CSV file which contains 10,000 lines of call data. This is a subset of data taken randomly
from an original file containing over 5 million lines of call data. To enhance the speed of analysis and
due to GitHub restrictions, the smaller file was used.

[Table of Contents](#table-of-contents)

## Blog Post Functions
- vals_by_col: This function returns all unique values for specified columns in a DataFrame.
- date_to_col: This function splits a single entry containing information about date and time, returning a DataFrame with the information split into individual columns.
- secondary_unique: This function returns either a list of dictionaries or a DataFrame which contains the number of times each unique in a certain column intersects with values from a secondary column (associated appearances).
- counts_to_portions: Given a DataFrame with counts as the datapoints, this function will return a DataFrame with the datapoints turned into a proportion, calculated by total of rows and columns, or by column or row total.
- expand_categories: Given a single datapoint to plug into a model which has been encoded (i.e. each categorical value has been encoded by the binary method), this function will expand the categorical data from the input to match the input required for the model.

[Table of Contents](#table-of-contents)


## Summary of the Analysis
The main Jupyter notebook has much insight to offer, however a summary of the main
findings can be found [here.](https://medium.com/@carlj.klein/emergency-call-placed-priority-pending-3c59e3c7ba42)
[Table of Contents](#table-of-contents)