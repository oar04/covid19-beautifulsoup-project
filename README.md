# COVID-19 Web Scraper

A personal practice project to further familiarise myself with BeautifulSoup and its basic functions by scraping data from a covid-19 stat tracking website.

This project is a Python script that scrapes COVID-19 data from the Worldometer website and saves it in a CSV file. It utilizes the BeautifulSoup library for web scraping and the pandas library for data manipulation.

## Prerequisites

Make sure you have the following installed on your system:

- Python (version 3.6 or above)
- BeautifulSoup (install via `pip install beautifulsoup4`)
- pandas (install via `pip install pandas`)

## Usage

1. Clone the repository or download the script file (`covid_data_scraper.py`) to your local machine.

2. Open the script file in a text editor or Python IDE.

3. Ensure the `url` variable to is accurate to the URL of the Worldometer website as urls can change and impact the functionality of the webscraper.

4. Run the script by executing the command `python covid_data_scraper.py` in the terminal or command prompt.

5. The script will fetch the data from the website, parse it using BeautifulSoup, and save it in a CSV file named `covid_data_today.csv` in the same directory.

6. Once the script finishes running, you can find the generated CSV file with the scraped COVID-19 data.

## Output

The script creates a CSV file (`covid_data_today.csv`) containing the following COVID-19 data for different countries:

- Country
- Total Cases
- New Cases
- Total Deaths
- New Deaths
- Total Recovered
- Active Cases
- Critical Cases
- Total Cases/1M population
- Deaths/1M population
- Total Tests
- Tests/1M population
- Population

## Acknowledgments

- This script was created as a learning exercise and demonstration of web scraping using Python with help from https://medium.com/analytics-vidhya/how-to-scrape-a-table-from-website-using-python-ce90d0cfb607
- Thank you to the BeautifulSoup and pandas libraries for their powerful functionalities.
