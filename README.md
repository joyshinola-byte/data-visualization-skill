# AAPL Stock Data Understanding & Exploratory Analysis

## Project Overview

This project focuses on understanding and exploring **Apple Inc. (AAPL) stock market data** using Python. The dataset contains daily stock price information such as Open, High, Low, Close, and Volume.

The project uses **Pandas** for data handling and **Matplotlib** for data visualization.

## Objectives

The main objectives of this project are:

* To load the AAPL stock dataset.
* To understand the structure of the dataset.
* To examine the first and last records.
* To check the number of rows and columns.
* To identify the available columns.
* To understand the data types and dataset information.
* To visualize Open, High, Low, and Close prices.
* To visualize the trading volume.
* To calculate and visualize 20-day and 50-day moving averages.
* To understand the overall stock price movement.

## Technologies Used

* **Python**
* **Google Colab**
* **Pandas**
* **Matplotlib**
* **Microsoft Excel** for the input dataset

## Dataset

The project uses an **AAPL stock dataset** stored in Excel format.

The dataset contains the following important attributes:

| Column | Description                  |
| ------ | ---------------------------- |
| Date   | Date of stock trading        |
| Open   | Opening price of the stock   |
| High   | Highest price during the day |
| Low    | Lowest price during the day  |
| Close  | Closing price of the stock   |
| Volume | Number of shares traded      |

## Data Loading

The dataset is loaded using Pandas:

```python
df = pd.read_excel('/content/drive/MyDrive/DV SKILL /AAPL.xlsx')
```

## Data Understanding

The following functions are used to understand the dataset:

```python
df.head()
df.tail()
df.shape
df.columns
df.info()
```

These functions help to view the records, identify the size of the dataset, check column names, and understand the data types.

## Data Visualization

### 1. AAPL OHLC Prices

The Open, High, Low, and Close prices are plotted to understand the daily stock p
