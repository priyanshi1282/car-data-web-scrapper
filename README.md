# car-data-web-scrapper

This repository contains the submission for my Introduction to Data Science module during the Autumn 2025 semester at University College Dublin (UCD).

## 📌 About the Project

The objective of this assignment was to extract a real-world dataset using web scraping, clean and prepare the data using Python, and perform detailed exploratory data analysis (EDA) to derive meaningful insights.

## Notebook Overview

####  📌 first.ipynb

1. Performs web scraping using urllib and BeautifulSoup.

2. Extracts used-car listings from multiple web pages, handles pagination, and parses both HTML tables and headings.

3. Stores the cleaned results into CSV files for analysis.

#### 📌 second.ipynb

1. Loads the scraped data into pandas DataFrames.

2. Cleans and transforms inconsistent fields such as date formats, mileage, and price formatting.

3. Visualizes trends using matplotlib.pyplot (histograms, scatter plots, etc.).

4. Includes detailed documentation for clarity and reproducibility.

## 🧩 Discussion Section
#### 🔹 Challenges Faced

1. Inconsistent Date Formats: Mixed formats (dd/mm/yyyy and yyyy-mm-dd) required robust parsing logic.

2. Irregular Mileage Entries: Some mileage values contained the word “miles,” while others did not.

3. Price Formatting: Currency symbols and commas had to be removed before converting to numeric values.

4. Pagination: Each of the four car brands had multiple pages, requiring automated navigation.

5. Complex HTML Structure: Car details were split between a heading and a table, which needed to be merged into a unified dataset.

#### 📊 Key Insights

1. Expensive cars typically have lower mileage, which is desirable for second-hand buyers.

2. Hatchbacks and SUVs were the most common categories in the dataset.

3. Mercedes-Benz had the highest average car price, while Volkswagen had the lowest.

4. Most cars were sold around €25,000, as shown in the price distribution analysis.

#### 🚀 Future Work

1. This project can be enhanced by:

2. Adding more data including fuel efficiency, customer ratings, and engine size.

3. Building predictive models (Regression / ML) to estimate car prices.

4. Observing price trends over time.

5. Grouping cars into budget, mid-range, and luxury categories for deeper insights.
