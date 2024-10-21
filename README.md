## Mars Web Scraping & Data Analysis

![Image Source](https://www.universetoday.com/wp-content/uploads/2013/11/mars.jpg)


## Overview

This project involves web scraping and data analysis using Python, Beautiful Soup, and Splinter. The task is divided into two parts:

1. **Scraping Mars news articles** – extracting titles and preview text.
2. **Scraping and analyzing Mars weather data** – analyzing temperature and atmospheric pressure data.

You will implement automated browsing to collect and process the data, store it in appropriate structures, and perform analyses. The results will be saved in a CSV file, with all deliverables presented in Jupyter Notebooks.

## Deliverables

### Deliverable 1: Scrape Mars News Articles
- Scrape titles and preview text from the Mars News website.
- Store the results in a Python dictionary, with each article having `title` and `preview` as keys.


### Deliverable 2: Scrape and Analyze Mars Weather Data
- Scrape weather data from the Mars Temperature Data Site and organize it into a Pandas DataFrame.
- Ensure the DataFrame contains the following columns:
  
          id, terrestrial_date, sol, ls, month, min_temp, pressure
- Analyze the data by answering:
  
       1 How many months exist on Mars?
       2 How many Martian days of data are in the dataset?
       3 What is the coldest and warmest month on Mars (average minimum temperature)?
       4 What is the month with the lowest and highest atmospheric pressure (average)?
       5 How many terrestrial days exist in a Martian year?
