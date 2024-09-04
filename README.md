# Mars News Scraper & Weather Data Analysis

## Overview
This project involves web scraping and data analysis tasks related to Mars. The project is split into two main parts:
1. Scraping Mars news articles' titles and preview text.
2. Scraping and analyzing Mars weather data, including cleaning, visualizing, and deriving insights from the data.

By completing these tasks, the project demonstrates the use of web scraping tools like BeautifulSoup and Splinter, data manipulation using Pandas, and data visualization using Matplotlib.

---

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Data Source](#data-source)
- [Installation](#installation)
- [Usage](#usage)
  - [Part 1: Scrape Mars News](#part-1-scrape-mars-news)
  - [Part 2: Scrape and Analyze Mars Weather Data](#part-2-scrape-and-analyze-mars-weather-data)
- [Analysis](#analysis)
  - [Minimum Temperature Analysis](#minimum-temperature-analysis)
  - [Atmospheric Pressure Analysis](#atmospheric-pressure-analysis)
  - [Estimating Martian Year Length](#estimating-martian-year-length)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Project Structure
This project consists of the following files:

- **part_1**: mars_news.ipynb # Jupyter notebook to scrape Mars news articles
- **part_2**: mars_weather.ipynb # Jupyter notebook to scrape and analyze Mars weather data
- **mars_weather_data.csv**: CSV file containing cleaned Mars weather data


---

## Data Source
- **Mars News**: The Mars news is scraped from the following website: [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html).
- **Mars Weather Data**: Mars weather data is scraped from the following page: [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).

---

## Installation
To run this project locally, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/mars-weather-analysis.git
   cd mars-weather-analysis
# Usage

## Part 1: Scrape Mars News
- Open the notebook part_1_mars_news.ipynb.
- Run the notebook cells to:
- Scrape the Mars news titles and preview text using Splinter and BeautifulSoup.
- Store the scraped data in a list of dictionaries, with each dictionary containing a title and its preview text.
- 
## Part 2: Scrape and Analyze Mars Weather Data

- Open the notebook part_2_mars_weather.ipynb.
- Run the notebook cells to:
- Scrape the Mars weather data (e.g., temperature, pressure).
- Clean and convert the scraped data into a Pandas DataFrame.
## Analyze the data to answer the following questions:
- How many months exist on Mars?
- How many sols (Martian days) are represented in the dataset?
- What are the coldest and hottest months?
- What are the months with the highest and lowest atmospheric pressure?
- Estimate the number of Earth days in a Martian year.
- Visualize the results using bar charts and line plots.
# Analysis
## Minimum Temperature Analysis
- **Coldest Months**: By analyzing the data, the coldest months on Mars at Curiosity's location were identified.
- **Hottest Months**: Similarly, the hottest months were identified by averaging daily minimum temperatures for each Martian month.
## Atmospheric Pressure Analysis
- **Lowest Pressure Months**: The month with the lowest average atmospheric pressure was found.
- **Highest Pressure Months**: The month with the highest average pressure was also identified by calculating the monthly averages.
## stimating Martian Year Length
- By plotting the daily minimum temperature over Earth days, a repeating cycle can be observed. This cycle corresponds to a Martian year, which is approximately 687 Earth days.
## Results
- The project successfully scraped Mars news articles and Mars weather data.
- It performed analysis on temperature and atmospheric pressure to identify trends and answered key questions about the Martian environment.

## Contributing
- Contributions are welcome! Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


