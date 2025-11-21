# IBM_Data_Science__Python_Project_for_Data_Science

## Project Overview

In this course, I developed foundational Python skills for data science through a hands-on project. Key activities included:

* **Data Extraction**: Utilized web scraping techniques to gather real-world data.
* **Data Analysis**: Employed Pandas for data manipulation and analysis, identifying patterns and trends.
* **Data Visualization**: Created visual representations of data using Plotly, enhancing insights and understanding.
* **Dashboard Development**: Built an interactive dashboard in Jupyter Notebook to present findings effectively.

This project not only showcased my proficiency in Python and relevant libraries but also strengthened my ability to apply data science concepts in practical scenarios.

## Project Details: Stock and Revenue Analysis

This hands-on lab focused on extracting and visualizing historical stock and revenue data for **Tesla (TSLA)** and **GameStop (GME)**. The project demonstrates practical applications of data extraction, cleaning, and visualization techniques.

### Key Components

#### 1. Stock Data Extraction
- Used **yfinance** library to extract historical stock data
- Retrieved maximum available historical data for both Tesla and GameStop
- Created structured DataFrames with Date, Open, High, Low, Close, Volume, and other metrics

#### 2. Revenue Data Extraction
- Implemented **web scraping** using BeautifulSoup and requests libraries
- Scraped quarterly revenue data from HTML tables
- Parsed HTML data using `html.parser` to extract structured information

#### 3. Data Cleaning and Preprocessing
- Removed special characters (dollar signs and commas) from revenue data
- Handled missing values and empty strings
- Reset DataFrame indices for proper data structure
- Ensured data consistency for visualization

#### 4. Interactive Visualizations
- Created dual-panel graphs using **Plotly** with:
  - Historical Share Price (top panel)
  - Historical Revenue (bottom panel)
- Implemented interactive features including zoom, pan, and range selectors
- Generated dashboards displaying data up to June 2021

### Technologies Used

- **Python Libraries**:
  - `yfinance`: Stock data extraction
  - `pandas`: Data manipulation and analysis
  - `requests`: HTTP requests for web scraping
  - `BeautifulSoup`: HTML parsing
  - `plotly`: Interactive data visualization

### Project Structure

The notebook is organized into 6 main questions:
1. Extract Tesla stock data using yfinance
2. Web scrape Tesla revenue data
3. Extract GameStop stock data using yfinance
4. Web scrape GameStop revenue data
5. Visualize Tesla stock and revenue
6. Visualize GameStop stock and revenue

### Skills Demonstrated

- API integration with financial data sources
- Web scraping and HTML parsing
- Data cleaning and transformation
- DataFrame manipulation with Pandas
- Interactive data visualization
- Creating professional dashboards for stakeholder presentation

### Outcome

Successfully created comprehensive visualizations comparing stock performance and revenue trends for Tesla and GameStop, providing insights into their financial performance over time.
