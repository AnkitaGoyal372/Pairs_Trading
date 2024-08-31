# Pairs Trading Using Cointegration Analysis

This project implements a pairs trading strategy leveraging cointegration analysis to identify and trade cointegrated stock pairs. The focus is on the banking sector, but the methodology can be extended to other sectors.

## Overview

Pairs trading involves trading two correlated stocks based on their price spread. The strategy uses cointegration analysis to find pairs where the price spread is mean-reverting.

## Data Collection

Stock prices are collected from Yahoo Finance for various sectors. This example primarily uses stocks from the banking sector.

## Analysis

- **Cointegration Testing**: Stocks are tested for cointegration using the Engle-Granger two-step method.
- **Spread Calculation**: The spread between cointegrated pairs is calculated.
- **Signal Generation**: Trade signals are generated based on the z-score of the spread.
- **Profit Calculation**: The profitability of the trading strategy is assessed.

