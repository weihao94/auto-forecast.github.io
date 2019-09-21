# The Auto Stock Forecasting Application

## Introduction

This standalone Python-based application is able to perform live extraction of stock data from Yahoo Finance, and from a set of predefined models, computes the daily forecast predictions for the months ahead.

## User Instructions

### Downloading the Application

The program can be download via: https://www.dropbox.com/s/v1ts5w5jpnyls6o/main.zip?dl=0. You should be able to observe the following:
<br>
<img src="img/dropbox.png?raw=true"/>
<br>
Once downloaded, unpack the archive and you should see the following folders inside the `main` folder:
<br>
<img src="img/main_folder.png?raw=true"/>
<br>

## Running the Program

Scroll down in the `main` folder till you arrive at `main.exe`:

<img src="img/main_folder_mainexe.png?raw=true"/>

Double click on it to open (it may take over 20 seconds to boot up initially), and a window should appear:

<img src="img/app_1.png?raw=true"/>

## Navigating the Program

There are instructions at each step of the program and it should be easy to follow. For simplicity, we illustrate the running of the program with performing a live extraction for the six default stocks, and compute their forecasts. So at step 1, we select `y` and the program proceeds to extract the data (internet connection required) for the six stocks:

<img src="img/screenshot_1.png?raw=true"/>

Once all the data have been extracted, the model computes the forecast for each stock in the sequence it was extracted. 