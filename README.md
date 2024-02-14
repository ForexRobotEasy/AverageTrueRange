# AverageTrueRange ReadMe

This is the ReadMe file for the code `AverageTrueRange.mq5`.

## Overview
This code calculates the Average True Range (ATR) indicator for a specified number of days. ATR is a popular volatility indicator used in technical analysis to measure the average range between the high and low prices of an asset over a specified period. This indicator can be useful for intraday traders to determine potential price movements and set appropriate stop-loss levels.

## Disclaimer
Please note that Forex Robot Easy Team is not the official developer of this product. This code is provided as a sample that can work similarly to the described product. To find the official developer of this product, please refer to MQL5.

## Input Parameters
The code defines an input parameter `period` which represents the number of days to calculate the Average True Range. By default, the period is set to 14.

## Calculation of Average True Range
The code calculates the Average True Range by iterating through the specified number of days. For each day, it calculates the true range, which is the maximum value among the difference between the high and low prices, the absolute difference between the high and previous close prices, and the absolute difference between the low and previous close prices. The true range values are then summed up, and the average is calculated by dividing the sum by the specified period.

## Usage
The code can be used as a standalone indicator or incorporated into a larger trading strategy. It provides the calculated Average True Range as a print statement in the `OnInit` function and also on each tick in the `OnTick` function.

## Errors Handling
The code includes an `OnError` function that handles any errors that occur during the execution of the code. It prints the error message to the console.

## Product Description
For detailed reviews and trading results of the official product associated with this code, please visit [AverageTrueRange Review - Master Intraday Trading Volatility](https://forexroboteasy.com/forex-robot-review/averagetruerange-review-master-intraday-trading-volatility/). This product aims to provide traders with a reliable tool for measuring volatility and making informed trading decisions. The official developer of this product can be found using MQL5.

------------------------------------------------------------------

Please note that the code provided above is a sample and may require additional modifications or integration with other components to work properly in a trading environment.
