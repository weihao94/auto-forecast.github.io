# The Auto Stock Forecasting Application

## Introduction

This standalone Python-based application is able to perform live extraction of stock data from Yahoo Finance, and from a set of predefined models, computes the daily forecast predictions for the months ahead. In the current build of the public version of the application, the program uses Facebook's `fbprophet` Python library for forecasting. The amount of historical data the program takes in is at most 2 years back, from the current date. It will then proceed to perform forecasts for each stock, for a full year ahead. An example of the output for the stock FB is as follows.

<img src="img/FB_forecast.png?raw=true"/>

## User Instructions

### Downloading the Application

The program can be download via this [link](https://www.dropbox.com/s/v1ts5w5jpnyls6o/main.zip?dl=0). You should be able to observe the following:
<br>
<img src="img/dropbox.png?raw=true"/>
<br>
Once downloaded, unpack the archive and you should see the following folders inside the `main` folder:
<br>
<img src="img/main_folder.png?raw=true"/>
<br>

### Running the Program

Scroll down in the `main` folder till you arrive at `main.exe`:

<img src="img/main_folder_mainexe.png?raw=true"/>

Double click on it to open (it may take over 20 seconds to boot up initially), and a window should appear:

<img src="img/app_1.png?raw=true"/>

### Navigating the Program

There are instructions at each step of the program and it should be easy to follow. For simplicity, we illustrate the running of the program with performing a live extraction for the six default stocks, and compute their forecasts. So at step 1, we select `y` and the program proceeds to extract the data (internet connection required) for the six stocks:

<img src="img/screenshot_1.png?raw=true"/>

Once all the data have been extracted, the model computes the forecast for each stock in the sequence it was extracted. An example of the program moving on to the next stock is shown below:

<img src="img/screenshot_2.png?raw=true"/>

Finally, when all stocks chosen initially have their forecasts computed, the program terminates, as shown below:

<img src="img/screenshot_3.png?raw=true"/>

### The Output Files - Forecast Plots & Forecasted Data

When the program terminates, to find your forecasts for each stock in the form of a plot (daily), the forecast components and the more detailed forecasted data, navigate to the folder `results` in `main/results`:

<img src="img/results_folder.png?raw=true"/>

Recall that if you have extracted stock data previously, they can be found in the `data` folder via `main/data`:

<img src="img/data_folder.png?raw=true"/>

Hope the guide helps!

-----

## Donate

If you will like to make contributions to the site (completely obligatory), click [here](https://weihao94.github.io/auto-stock-forecasting-app/pages/donate).