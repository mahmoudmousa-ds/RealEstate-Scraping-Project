# Real Estate Market Analysis in Riyadh
![img](<dashboard.jpg>)
## Project Overview
![alt text](image.png)

This project focuses on analyzing the real estate market in the Riyadh region by scraping data from the **Bayut** website, cleaning and transforming it, performing feature engineering, and visualizing insights using 
**Power BI and python**.


## Data Collection
- **Source:** Bayut website (https://www.bayut.sa/)
- **Method:** Web scraping using `BeautifulSoup` and `requests`
- **Entries Scraped:** 7,200 real estate listings
- **Script:** The web scraping process is implemented in `Scraper.ipynb`

## Data Processing
- **Cleaning:** Conducted in **Power Query**, including handling missing values, formatting data, and standardizing variables.
- **Feature Engineering:** Created additional insights from raw data, such as price per square meter, property type segmentation, and location-based aggregations.

## Visualization
- **Tool Used:** Power BI
- **Key Insights Displayed:**
  - Distribution of properties by district
  - Property type breakdown
  - Average price and area by property type
  - Market trends and pricing analysis

## Files in the Repository
- `Scraper.ipynb` - Jupyter Notebook containing the web scraping script.
- `bayut_properties.csv` - Cleaned dataset extracted from the Bayut website.
- `Real Estate Market in Riyadh.pdf` - Power BI dashboard visualizing key insights.

## Next Steps
- Enhance feature engineering to include time-series analysis of price trends.
- Integrate geospatial analysis for better location-based insights.
- Automate data updates with scheduled web scraping and ETL processes.

## Author
**Mahmoud** – Data Scientist passionate about real estate analytics and data-driven insights.