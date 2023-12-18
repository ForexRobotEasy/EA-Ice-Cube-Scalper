# EA Ice Cube Scalper

This is a Forex trading software, EA Ice Cube Scalper, developed by Forex Robot Easy Team. It is a trend-based scalping EA that uses the RSI indicator to identify trends and execute scalping trades. The main objective of the software is to make multiple trades daily and aim to take several points with each transaction.

## Features

- Trend-based scalping strategy: The software uses the RSI indicator to identify trends and make trading decisions.
- Averaging with lot multiplier: The software incorporates a concept of averaging with a lot multiplier into its strategy.
- Risk control measures: The software has risk control measures in place to limit the maximum number of orders for averaging and equity risk.
- Backtesting functionality: The software allows for backtesting to assess its performance and make necessary adjustments.

## How it works

The software executes scalping trades based on the RSI indicator. It calculates the lot size based on the available balance and the maximum equity risk percentage. The lot size is then used to open buy or sell orders when the RSI indicator signals a trend reversal.

If the current RSI value is above 70 and the previous RSI value is below or equal to 70, a buy order is opened. The stop loss is set at 50 pips below the entry price, and the take profit is set at 100 pips above the entry price.

If the current RSI value is below 30 and the previous RSI value is above or equal to 30, a sell order is opened. The stop loss is set at 50 pips above the entry price, and the take profit is set at 100 pips below the entry price.

The software also incorporates averaging with a lot multiplier into its strategy. If the total number of open orders is less than the maximum allowed orders, the software opens an averaging order with an increased lot size based on the current lot size and the multiplier.

## Product Description

The EA Ice Cube Scalper is a trend-based Forex trading software developed by Forex Robot Easy Team. It uses the RSI indicator to follow trends and execute scalping trades in the Forex market. The software aims to take several points with each transaction and make multiple trades daily.

One of the key features of the EA Ice Cube Scalper is its ability to incorporate averaging with a lot multiplier into its strategy. This allows the software to increase the lot size for averaging orders, potentially increasing the profitability of trades.

The software also includes risk control measures to limit the maximum number of orders for averaging and equity risk. This helps to manage the overall risk exposure of the software and protect the trading account.

Backtesting functionality is also included in the software, allowing users to assess its performance and make necessary adjustments. This helps to optimize the software's settings and improve its overall trading performance.

Please note that Forex Robot Easy is not the official developer of this product. We are only showcasing sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - EA Ice Cube Scalper Review](https://forexroboteasy.com/forex-robot-review/ea-ice-cube-scalper-review-trend-based-forex-trading-software/).
