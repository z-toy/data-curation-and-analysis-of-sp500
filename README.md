# Data Curation and Analysis of the S&P 500

## Data
The data is taken from the following reference: Wikipedia contributors. (2023, February 23). List of S&P 500 companies. Wikipedia. https://en.wikipedia.org/wiki/List_of_S%26P_500_companies.

The S&P 500 constituents are rebalanced on a quarterly basis on the third Friday of March, June, September and December on the basis of their weighting and other relevant factors. The Wikipedia page containing this S&P 500 list was last edited on February 23, 2023.

A notable quirk in the data was that some of the companies was founded at unknown dates before 1985, and we thus given <1985 in the "Founded" column. I removed the < and kept the year 1985 for these data points. 

Additionally, some of the data points contained two dates for the year added to the S&P 500. This was because they were added, removed, and then readded to the list. I removed the original date and kept the year the company was most recently added.

There are no potential biases I am aware of. 

## Analysis
From the data, I wanted to see if there were any trends in the types of companies in the S&P 500 and when they were added to the list. I created a histogram, boxplot, regression plot, and scatterplot using Seaborn to visualize and analyze the data. From these data visualizations, came to the following conclusions:

* Out of the companies in the S&P 500, majority fall into Global Industry Classification Standard (GICS) category of Industrials, Health Care, Information Technology, and Financials.
* On average, the S&P 500 companies that fall under the Communication Services category were most recently added to the list (mid 2010s), with Information Technology falling closely behind. In contrast, the companies that fall under the Consumer Staples category were added earliest (mid 1980s).
* There is moderate positive association between the year a company was founded and the date it was added to the S&P 500.
