# Blog Post: Emergency Calls
This project analyzes call data to the Seattle Police Department call center, and was
provided by the city of Seattle.

The most recent data can be accessed [here](https://data.seattle.gov/Public-Safety/Call-Data/33kz-ixgy):

## Table of Contents
- [Libraries Used](#libraries)
- [Project Motivation](#motivation)
- [File Descriptions](#files)
- [Summary of the Analysis](#summary)


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

1. Was times were the majority of the calls placed? Are there any surges by
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


## Summary of the Analysis
The main Jupyter notebook has much insight to offer, however a summary of the main
findings can be found [here].
[Table of Contents](#table-of-contents)