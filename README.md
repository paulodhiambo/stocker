# Stocker - Stock Price Predictor

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/paulodhiambo/stocker)
![GitHub repo size](https://img.shields.io/github/repo-size/paulodhiambo/stocker)
![GitHub language count](https://img.shields.io/github/languages/count/paulodhiambo/stocker)
![GitHub last commit](https://img.shields.io/github/last-commit/paulodhiambo/stocker)

Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a stock's future price could yield significant profit. The efficient-market hypothesis suggests that stock prices reflect all currently available information and any price changes that are not based on newly revealed information thus are inherently unpredictable. Others disagree and those with this viewpoint possess myriad methods and technologies which purportedly allow them to gain future price information.

We make use of Facebook's Time Series forcasting algorithm Prophet to predict stock market price of US based companies in real time using multi-variate, single step forecasting strategy.

![Header](index.png)

## Getting Started

Download or clone project from github:
```
$ git clone https://github.com/paulodhiambo/stocker.git
```

Create a project environment (Anaconda recommended):
```
$ conda create --name envname python
$ conda activate envname
```

Install prerequisites:
```
$ pip install -r REQUIREMENTS.txt
```

Run project:
```
$ cd stocker
$ python runserver.py
```

## Model Validation Analysis

**Facebook (Stock: FB) Validation**
![FB_validation](fb_forecast_30_day_validation.png)

**Microsoft (Stock: MSFT) Validation**
![MSFT_validation](msft_forecast_30day_validation.png)

**Google (Stock: GOOGL) Validation**
![GOOGLE_validation](googl_forecast_30day_validation.png)
