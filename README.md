# Mars Data Web Scraping and Analysis

## Overview

This project involves web scraping data from the Mars News website and Mars Temperature Data Site. The collected data is then analyzed using Python, particularly the libraries Splinter, BeautifulSoup, and Pandas. The analysis includes scraping titles and preview text from Mars news articles and extracting and analyzing Mars weather data from an HTML table.

## Files

### Part 1: Scrape Titles and Preview Text from Mars News

- **File:** `part_1_mars_news.ipynb`
- **Instructions:**
  - Use automated browsing with Splinter to visit the Mars News site.
  - Create a Beautiful Soup object to extract text elements.
  - Store the scraped data in Python dictionaries and a list.
  - Optionally, export the data to a JSON file.

### Part 2: Scrape and Analyze Mars Weather Data

- **File:** `part_2_mars_weather.ipynb`
- **Instructions:**
  - Use automated browsing with Splinter to visit the Mars Temperature Data Site.
  - Create a Beautiful Soup object to scrape data from an HTML table.
  - Assemble the scraped data into a Pandas DataFrame.
  - Analyze the data and answer specific questions.
  - Export the DataFrame to a CSV file.

## Instructions

- Open part_1_mars_news.ipynb to scrape titles and preview text from the Mars News website.
- Open part_2_mars_weather.ipynb to scrape and analyze Mars weather data.
- Follow the instructions in the code comments for each part.
- Ensure you have the required libraries installed (Splinter, BeautifulSoup, Matplotlib, Pandas).

## Results

- Part 1: A list of dictionaries containing titles and preview text from Mars news articles.
- Part 2: Analyzed Mars weather data with answers to specific questions and visualizations.
  
Data exported to mars_data.csv.

## Dependencies
- Splinter
- BeautifulSoup
- Matplotlib
- Pandas
