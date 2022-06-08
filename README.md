# Web-Scraping-and-Data-Analysis-project
Web-Scraping-and-Data-Analysis project-on-Economic-impact-of-COVID-19.

### Problem statement :
- The impact of COVID-19  on India has been largely disruptive in terms of economic activity, since there was a 3 month lockdown in India. Almost all the sectors have been adversely affected as domestic demand and exports sharply plummeted with some notable exceptions where high growth was observed. 
- An attempt is made to analyze the impact during pre and post crisis and possible solutions for some key market elements.

### Life Cycle of the Project:
- Business Understanding (Domain knowledge)
- problem statement
- Data Collection (Web Scraping)
- Data Cleaning ( Missing Data, Pre processing)
- Data Analysis (EDA) to know insights about data

### Understanding the features
- Date - Pre and post COVID period from 2019-06-01 to  2021-07-31 for 792 days, all the data below was collected for this time period respectively.                
- Covid cases - Number of COVID positive cases recorded per day.

#### Prices
- USD( $ ) to INR( ₹ ) - Historical data for US Dollar (USD) to Indian Rupee (INR) exchange rates.
- (Monthly average prices are converted into daily prices,without a change in the average for Crude oil & Gold Price)
- Crude oil ( ₹ / Barrel ) - Crude oil monthly average price for Indian Rupee per Barrel
- Gold Price( ₹ / Troy ounce ) - Monthly average gold price for Indian Rupee per troy ounce( 1 Troy ounce = 31.1035 grams)
- Food Price Index - Commodity Food Price Index,includes Cereal, Vegetable Oils, Meat, Seafood, Sugar, Bananas, and Oranges Price Indices.(Monthly average prices are converted into daily prices,without a change in the average)
#### Stock market
(NIFTY - a benchmark Indian stock market index that represents the weighted average of 50 of the largest Indian companies listed on the National Stock Exchange.)
- NIFTY_50 - daily index points of all sectors.
- NIFTY_IT - daily index points of IT sector companies.                 
- NIFTY_BANK - daily index points of Banking sector.

### Web Scraping sources
- -https://en.wikipedia.org/w/index.php?title=Template:COVID-19_pandemic_data/India_medical_cases_chart&action=edit
- -https://www.exchangerates.org.uk/USD-INR-spot-exchange-rates-history.html
- -https://www.indexmundi.com/commodities/?commodity=crude-oil&months=60&currency=inr
- -https://www.indexmundi.com/commodities/?commodity=gold&months=60&currency=inr
- -https://www.indexmundi.com/commodities/?commodity=food-price-index&months=60
- -Getting Stock data using Yahoo finance API


### Steps Involved

- Identify the URL from which you need the data.
- Inspect the HTML code behind the page.
- Find the elements you want to extract.
- Store the data in the required format.

### Files attached
1. Jupyter notebook with python code file with data cleaning.
2. Jupyter notebook with visualization and EDA.


   





