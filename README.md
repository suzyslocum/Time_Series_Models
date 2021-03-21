# Module 11 Challenge Assignment

## Using Time Series Models to Analyze Stock Price Corrleation to Search Traffic
This is a Python application written with Pandas in Google Colab to examine Google Search traffic and stock prices for MercadoLibre, the most popular e-commerce site in Latin America. It uses Pandas to create DataFrames from provided CSV files, and create various graphs to analyze search traffic seasonality. We use this along with stock closing prices to evaluate how the stock prices correlate to the Google Search traffic. HvPlot is used to create interactive graphs to examine the data. We then use a Prophet forecast model to predict and visualize hourly search traffic, and the company's future revenue.

![Search Trends](/Images/search_trends_wk_of_yr.jpg)
![Closing Prices](/Images/closing_price.jpg)
![Close vs Search](/Images/close_vs_search.jpg)
![Correlation table](/Images/corr_table.jpg)
![Revenue Forecast](/Images/rev_forecast.jpg)


---

## Technologies

The application is written in Python using Pandas in Google Colab

The following packages are used:

Pandas - to write and run the program [Pandas documentation](https://pandas.pydata.org/docs/)

hvPlot - to create graphs [hvPlot documentation](https://hvplot.holoviz.org/)

HoloViews - to create graphs [HoloViews documentation](https://holoviews.org/user_guide/index.html)

matplotlib - to create graphs [matplotlib documentation](https://matplotlib.org/stable/contents.html)

fbprophet - to create forecast models - [fbprophet documentation](https://facebook.github.io/prophet/docs/quick_start.html)

datetime - to standardize the format of dates - [datetime documentation](https://docs.python.org/3/library/datetime.html)



---

## Installation Guide

Install the Pandas package using the following command: 'import pandas as pd'

Install the hvPlot library using the following command: 'import hvplot.pandas'

Install the HoloViews library using the following command: 'import holoviews as hv'

Install the matplotlib library using the following command: '%matplotlib inline'

Install the fbprophet library using the following command: 'from fbprophet import Prophet'

Install the datetime library using the following command: 'import datetime as dt'




--- 

## Usage

To run this program, clone the repository onto your computer, navigate to its source folder in your terminal and open Google Colab in a web browser. Run the 'forecasting_net_prophet.ipynb' file in Google Colab, uploading the apropriate CSV files as you run the cells.

---

## Contributors
Susannah Slocum 
suzyslocum@gmail.com

---

## License

None
