## car-data-web-scrapper
This repository is the submission of the assignment under <b>Introduction to DataScience</b> module during the autmn 20025 semester at University College Dublin.
### About
The objective of these notebooks is to extract a dataset from a set of web pages and use Python to prepare, analyse, and derive insights from the collected data.
1. Notebook first.ipynb contains web scraping in Python to collect and parse all of the data followed by storiing the collected data in .csv format for subsequent analysis. 
2. Notebook second.ipynb loads the collected dataset into dataframes (pandas library).
   
The data is also cleaned and transformed to perform analysis by ploting graphs/charts using pyplot library. Both the notebooks are documented to understand the working of the code.

### Discussion Section
1. Challenges Faced:
Inconsistent Date Format: The date field had two different types: dd/mm/yyyy and yyyy-mm-dd, which required parsing logic to clean it.
Irregular Mileage Entries: Some mileage fields had the word 'miles' in them while some did not have it, which needed data cleaning.
Price Formatting Issue: The price field had a currency symbol in some values which needed to be removed along with commas to convert it into float values.
Pagination Handling: The website had 4 car brands, and each brand had pagination which needed to be addressed.
Parsing HTML for Each Car Detail: The HTML for car details had a heading followed by a table, which then both needed to be combined into a single data list.
2. Key Insights:
Expensive cars have less mileage, which is considered a good factor for a second-hand car.
The leading car categories are Hatchback and SUV.
Mercedes-Benz is the most expensive brand, while Volkswagen has the lowest average price.
Most cars were sold around a price point of €25,000.
3. Further Work:
The current analysis could be extended in several ways:
Adding extra data to the set. For example, adding data about fuel efficiency and customer ratings can enhance the insights.
Building a regression or machine learning model to predict car prices based on factors such as year, brand, mileage, etc.
It can be analyzed how car prices evolve over time.
Cars can be grouped into luxury, budget, and mid-range categories.
