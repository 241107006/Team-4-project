# Real Estate Analysis Project using Booking.com

## Overview

This project focuses on analyzing real estate data by scraping hotel information from Booking.com, cleaning the collected data, and performing data analysis for insights. The project is divided into three main steps:

1. **Data Scraping**
2. **Data Cleaning and Preprocessing**
3. **Data Analysis**

## Project Files

### 1. `scraping_311.ipynb`
This notebook is responsible for scraping hotel data from the Booking.com website. It gathers key information such as hotel names, locations, prices, ratings, and amenities. The scraping process uses Python libraries such as `BeautifulSoup` and `requests` to extract data from the website's HTML structure.

### 2. `Concat.ipynb`
After scraping the data, this notebook is used for cleaning and formatting the raw data. It merges, organizes, and standardizes the dataset to ensure consistency across various columns, making it ready for analysis. This step also removes unnecessary or incomplete data points to ensure the dataset is clean and reliable.

### 3. `hotel_analysis.ipynb`
In this notebook, the cleaned data is analyzed to uncover valuable insights. This includes exploring patterns in hotel prices, ratings, and locations, as well as identifying trends or anomalies. Visualizations such as graphs and charts are created using libraries like `Matplotlib` and `Seaborn` to better understand the data.

## Notes

- The project files have been modified and iterated over multiple versions, and some functions or code may be missing or altered during the development process.
- The data scraping process is dependent on the current structure of the Booking.com website, which may change over time, affecting the scraping code's functionality.

## Technologies Used

- Python
- BeautifulSoup
- Pandas
- Matplotlib
- Seaborn

## Future Improvements

- Enhance error handling in the scraping process to manage potential website structure changes.
- Implement more advanced analysis techniques, such as machine learning models, to predict hotel prices or ratings.
- Expand the dataset by scraping additional information like customer reviews or geographical data.
