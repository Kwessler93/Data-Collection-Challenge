# Data-Collection-Challenge
Module 11 Challenge
# Data Collection Challenge: Mars News & Weather

## Project Overview
This project is part of a Data Collection Challenge, aimed at gathering and analyzing data related to Mars. The project consists of two main parts:

1. **Mars News Scraper** - Collects the latest Mars-related news articles.
2. **Mars Weather Data** - Gathers and processes weather data from Mars.

## Files Included
- `part_1_mars_news.ipynb`: A Jupyter Notebook for scraping and analyzing Mars news articles.
- `part_2_mars_weather.ipynb`: A Jupyter Notebook for collecting and processing Mars weather data.

## Installation & Dependencies
To run this project, ensure you have Python and Jupyter Notebook installed. You will also need the following Python libraries:

```bash
pip install requests beautifulsoup4 pandas jupyter matplotlib seaborn
```

## Usage
1. Clone the repository or download the project files.
2. Open Jupyter Notebook and navigate to the desired notebook.
3. Run the notebook cells sequentially to scrape and analyze the data.

## Analysis & Outputs
### Part 1: Mars News
- **Process:**
  - Scraped the latest news articles related to Mars from NASA's website.
  - Extracted article titles and summaries.
  - Cleaned and structured the data for easy analysis.
- **Output:**
  - Displayed the latest Mars news articles.
  - Created a summary table of extracted news.
  - Screenshot of output:
    ![Mars News Output](images/mars_news_output.png)

### Part 2: Mars Weather
- **Process:**
  - Collected weather data from the Mars Weather API.
  - Parsed the temperature, wind speed, and atmospheric pressure data.
  - Conducted basic exploratory data analysis (EDA).
  - Created visualizations for temperature trends and pressure variations.
- **Output:**
  - Generated descriptive statistics for weather data.
  - Plotted trends using matplotlib and seaborn.
  - Screenshot of output:
    ![Mars Weather Output](images/mars_weather_output.png)

## Data Sources
- Mars news articles are collected from [NASA](https://mars.nasa.gov/news/).
- Mars weather data is sourced from [Mars Weather API](https://mars.nasa.gov/insight/weather/).

## Contributors
- **Kimberly Wessler**

## License
This project is for educational purposes. Feel free to modify and use it!

