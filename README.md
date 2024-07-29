# Moving Average Calculation and Candlestick Chart

![Image](img/vis.png)

This repository contains a Jupyter notebook (`moving_average.ipynb`) that demonstrates how to calculate the moving average for a dataset and visualize it using a candlestick chart with Plotly. This notebook leverages the `HsTrader` library, a powerful tool for financial data analysis and trading strategies.

## HsTrader Library

`HsTrader` is a Python library designed for financial data analysis and trading strategy development. It provides a wide range of tools for technical analysis, including moving averages, candlestick patterns, and other indicators. This notebook uses `HsTrader` to facilitate the calculation of moving averages and the visualization of financial data.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Introduction

The purpose of this notebook is to:

1. Calculate the moving average of the 'close' prices in a given dataset using the `HsTrader` library.
2. Visualize the data using a candlestick chart with the moving average overlayed.

## Setup

To run this notebook, you need to have Python and Jupyter Notebook installed on your system. You also need to install the required Python packages.

### Installation

1. Clone this repository:

   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install the required packages:

   ```bash
   pip install pandas plotly HsTrader
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook moving_average.ipynb
   ```

## Usage

1. Open the `moving_average.ipynb` notebook in Jupyter Notebook.
2. Run the cells sequentially to:
   - Generate a sample dataset.
   - Calculate the moving average for the 'close' prices using `HsTrader`.
   - Visualize the dataset using a candlestick chart with Plotly, including the moving average.

## Dependencies

- pandas
- plotly
- HsTrader
- numpy

You can install the dependencies using pip:

```bash
pip install pandas plotly HsTrader numpy
```
