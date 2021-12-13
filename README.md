## :bulb: Knowledge Repository Projects

Here we present several projects/tutorials that illustrates how data science techniques are applied and how they can benefit businesses.

These projects were inspired on projects developed by data science and entrepreneurship master students of [JADS](https://www.jads.nl/) at [JADS MKB Datalab](https://jadsmkbdatalab.nl/) 
while helping many SME's becoming more data driven.

[:arrow_backward: **Back to repository main page**](https://github.com/MKB-Datalab/mkbdatalab_knowledge_repository_main)

## :computer: Projects
<!--ts-->

| Project | Tags |
| --- | --- |
| [**Basics on Web scraping**](https://github.com/MKB-Datalab/basics_web_scraping) | <img src="https://img.shields.io/badge/-Web%20Scraping -blueviolet"> <img src="https://img.shields.io/badge/-Python-blue"> |
| [**Basics on Retrieving Data with APIs**](https://github.com/MKB-Datalab/retrieving-data-with-apis) | <img src="https://img.shields.io/badge/-%20API -blueviolet"> <img src="https://img.shields.io/badge/-Python-blue"> |
| [**Time Series Analysis and Forecasting with SARIMAX and Facebook Prophet models: An Intro**](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet) | <img src="https://img.shields.io/badge/-%20Forecasting -yellow"> <img src="https://img.shields.io/badge/-%20ARIMA -yellow"> <img src="https://img.shields.io/badge/-%20statsmodel -yellowgreen"> <img src="https://img.shields.io/badge/-%20FacebookProphet -yellow">  <img src="https://img.shields.io/badge/-Python-blue"> |
| [**Marketing Analytics : Market Basket Analysis**](https://github.com/MKB-Datalab/marketing-analysis-part-1-market-basket-analysis) | <img src="https://img.shields.io/badge/-%20MarketingAnalytics -red"> <img src="https://img.shields.io/badge/-%20MarketBasketAnalysis -red"> <img src="https://img.shields.io/badge/-%20MLxtend -9cf"> <img src="https://img.shields.io/badge/-Python-blue"> |
    



[:arrow_backward: **Back to repository main page**](https://github.com/MKB-Datalab/mkbdatalab_knowledge_repository_main)

<!--te-->

## Projects' Summaries

<a name="basics-web-scraping"/></a>
###  [**Basics on Web Scraping**](https://github.com/MKB-Datalab/basics_web_scraping)
[Repository](https://github.com/MKB-Datalab/basics_web_scraping) | [Blog](https://jadsmkbdatalab.nl/web-scraping/)

<img src="https://github.com/MKB-Datalab/basics_web_scraping/blob/master/images/webpage_webscraping.JPG" height="200"/>

Web scraping allows us to retrieve data stored on web pages across the Internet. This is a very handy skill for a data scientist since sometimes 
the data we need is not available via APIs or datasets.

In this project/tutorial we show that is possible to web scrape using few knowledge on HTML and with help 
of Python packages [`requests`](https://requests.readthedocs.io/en/master/) and [`BeautifulSoup`](https://www.crummy.com/software/BeautifulSoup/bs4/doc/). We extract 
text, information from tables, and also from hyperlinks within a webpage.

Since data is what we get from web scraping the applications are endless. They go from a business, to governmental, until personal applications.  
	
<a name="retrieving-data-with-apis"/></a>
###  [**Basics on Retrieving Data with APIs**](https://github.com/MKB-Datalab/retrieving-data-with-apis)
[Repository](https://github.com/MKB-Datalab/retrieving-data-with-apis) | [Blog](https://jadsmkbdatalab.nl/retrieving-data-with-apis-an-intro/)

<img src="https://github.com/MKB-Datalab/retrieving-data-with-apis/blob/master/images/API_cover_Matthew_Henry_Burst.JPG" height="200"/>

In this tutorial we give an overview of how to use APIs (Application Programming Interfaces) to retrieve data. Via API one is able to retrieve real time 
data as well as historical data. An example of interesting business application involves combining real time data together with historical data to predict  demand of products.

We start this tutorial with some basics on JSON (JavaScript Object Notation) files which are standard form for transferring data through APIs. After that we start exploring 
some APIs starting by a simple one: The [Open Movie database (OMDb) API]( http://www.omdbapi.com/). Then we take a look on how to get information from both 
[NS]( https://apiportal.ns.nl/) and KNMI Weer APIs ([Weerlive]( https://weerlive.nl/delen.php) and [meteoserver]( https://meteoserver.nl/)).
To close it we check out how to pull data from [Twitter]( https://twitter.com/home?lang=en).
  
<a name="time-series-analysis-with-SARIMAX-and-Prophet"/></a>
###  [**Time Series Analysis and Forecasting with SARIMAX and Facebook Prophet models: An Intro**](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet)
[Repository](time-series-analysis-with-SARIMAX-and-Prophet) | [Blog part 01](https://jadsmkbdatalab.nl/an-introduction-to-time-series-analysis/) | [Blog part 02](https://jadsmkbdatalab.nl/forecasting-with-sarimax-models/) | [Blog part 03](https://jadsmkbdatalab.nl/forecasting-with-facebook-prophet-models-an-intro/)

<img src="https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/images/aron-visuals-BXOXnQ26B7o-unsplash.jpg" height="200"/>

**Time series analysis** deals with data that is ordered in time. Time series data is one of the most common data types and it is used in a wide variety of domains: finance, climate, health, energy, governance, industry, agriculture, business etc. Being able to effectively work with such data is an increasingly important skill for data scientists, especially when the goal is to report trends, forecast, and even detect anomalies.

In this tutorial we introduce some basics on time series analysis. We also give an overview some important models used to forecasting: ARIMA models and its variants, as well as the Facebook Prophet forecasting model.

This tutorial is divided in 3 parts each one presented in the following notebooks and blogs:

* [01-Intro_time_series_tutorial.ipynb](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/notebooks/01-Intro_time_series_tutorial.ipynb) | [Time Series Part 1: An Introduction to Time Series Analysis](https://jadsmkbdatalab.nl/an-introduction-to-time-series-analysis/)
* [02-Forecasting_with_SARIMAX.ipynb](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/notebooks/02-Forecasting_with_SARIMAX.ipynb) | [Time Series Part 2: Forecasting with SARIMAX models: An Intro](https://jadsmkbdatalab.nl/forecasting-with-sarimax-models/)
* [03-Forecasting_with_Facebook_Prophet.ipynb](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/notebooks/03-Forecasting_with_Facebook_Prophet.ipynb) | [Time Series Part 3: Forecasting with Facebook Prophet: An Intro](https://jadsmkbdatalab.nl/forecasting-with-facebook-prophet-models-an-intro/)

<a name="time-series-analysis-with-SARIMAX-and-Prophet"/></a>
###  [**Time Series Analysis and Forecasting with SARIMAX and Facebook Prophet models: An Intro**](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet)
[Repository](time-series-analysis-with-SARIMAX-and-Prophet) | [Blog part 01](https://jadsmkbdatalab.nl/an-introduction-to-time-series-analysis/) | [Blog part 02](https://jadsmkbdatalab.nl/forecasting-with-sarimax-models/) | [Blog part 03](https://jadsmkbdatalab.nl/forecasting-with-facebook-prophet-models-an-intro/)

<img src="https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/images/aron-visuals-BXOXnQ26B7o-unsplash.jpg" height="200"/>

**Time series analysis** deals with data that is ordered in time. Time series data is one of the most common data types and it is used in a wide variety of domains: finance, climate, health, energy, governance, industry, agriculture, business etc. Being able to effectively work with such data is an increasingly important skill for data scientists, especially when the goal is to report trends, forecast, and even detect anomalies.

In this tutorial we introduce some basics on time series analysis. We also give an overview some important models used to forecasting: ARIMA models and its variants, as well as the Facebook Prophet forecasting model.

This tutorial is divided in 3 parts each one presented in the following notebooks and blogs:


[:arrow_backward: **Back to repository main page**](https://github.com/MKB-Datalab/mkbdatalab_knowledge_repository_main)



<!--- ADD ANOTHER PROJECT THE SAME AS ABOVE --->

