# Project Title: Stock Data Analysis and Visualization for Investment Firm


As a Data Scientist and Data Analyst working for a startup investment firm, the goal of this project is to extract, analyze, and visualize financial data for selected stocks – Tesla, Amazon, AMD, and GameStop. The project involves a combination of web scraping, data extraction using Python libraries (yfinance, requests, BeautifulSoup), and creating interactive dashboards for effective data interpretation. The key components of the project include historical stock price analysis, quarterly revenue extraction, and visualizing the findings in a dashboard.

### Project Steps:

#### 1. Extracting Tesla Stock Data:
   - Utilized the `yfinance` library to extract historical stock data for Tesla (TSLA).
   - Used the `history` function with the period parameter set to 'max' to get information for the maximum available time.
   - Reset the index of the DataFrame for better data handling.

#### 2. Extracting Tesla Revenue Data:
   - Employed the `requests` library to download the revenue data webpage for Tesla.
   - Parsed the HTML data using BeautifulSoup, located the table containing revenue information, and extracted it.
   - Cleaned the revenue data by removing commas and dollar signs, ensuring numeric data for analysis.
   - Displayed the processed revenue data, showing Date and Revenue columns.

#### 3. Creating Graphs for Tesla Stock Data:
   - Defined a comprehensive function, `make_graph`, to create a graph that combines historical share price and revenue data.
   - Utilized Plotly to make subplots for share price and revenue on the same graph.
   - Limited the data to display up to June 2021 for better focus.
   - Displayed the graph with appropriate titles and labels for clear interpretation.

#### 4. Extracting GameStop Stock Data:
   - Used the `yfinance` library to extract historical stock data for GameStop (GME).
   - Used the `history` function with the period parameter set to 'max' to get information for the maximum available time.
   - Reset the index of the DataFrame for better data handling.

#### 5. Extracting GameStop Revenue Data:
   - Utilized the `requests` library to download the revenue data webpage for GameStop.
   - Parsed the HTML data using BeautifulSoup, located the table containing revenue information, and extracted it.
   - Cleaned the revenue data by removing commas and dollar signs, ensuring numeric data for analysis.
   - Displayed the processed revenue data, showing Date and Revenue columns.

#### 6. Creating Graphs for GameStop Stock Data:
   - Utilized the `make_graph` function to create a graph combining historical share price and revenue data for GameStop.
   - Employed Plotly to make subplots for share price and revenue on the same graph.
   - Displayed the graph with appropriate titles and labels for clear interpretation.

### Conclusion:
This project provides us valuable insights into the historical performance of Tesla and GameStop stocks, including their share prices and quarterly revenues. The interactive graphs generated through the `make_graph` function offer a visual representation of key financial metrics, aiding investment decisions. The project showcases the versatility of data science and analysis techniques in extracting, cleaning, and presenting financial data for informed decision-making in the context of stock investments.
