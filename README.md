# MT4 History Loader

MT4 History Loader is an expert advisor (EA) that allows you to download historical data from your broker's server directly into your MetaTrader 4 (MT4) platform. With this tool, you can easily access and analyze historical price data for multiple symbols and timeframes.

## Features

- Download historical data for multiple symbols and timeframes
- Specify the maximum number of bars to download for both history and chart
- Print progress updates on the Experts log
- Easy to use and configure

## Input Parameters

- Symbols: An array of symbols to download historical data for (default: EURUSD, GBPUSD, USDJPY)
- Timeframes: An array of timeframes to download historical data for (default: M1, H1, D1)
- MaxBarsInHistory: The maximum number of bars to download for history (default: 5000)
- MaxBarsInChart: The maximum number of bars to display on the chart (default: 1000)

## How it Works

1. The expert advisor initializes by setting the maximum number of bars in history and chart based on the input parameters.
2. Information about the selected symbols and timeframes is printed on the Experts log.
3. On each tick, the expert advisor checks if all bars have been downloaded. If so, a message is printed on the Experts log and the function exits.
4. The expert advisor loops through the selected symbols and timeframes.
5. For each symbol and timeframe, it checks if there are still bars to download.
6. If there are bars to download, it downloads the bars from the broker's server (implementation not provided in the code sample).
7. The number of downloaded bars is updated and progress is printed on the Experts log.

## Product Description

MT4 History Loader is a powerful tool that allows you to easily download historical data for multiple symbols and timeframes directly into your MT4 platform. With this expert advisor, you can access and analyze historical price data to make informed trading decisions.

This tool is designed to be user-friendly and highly customizable. You can specify the symbols and timeframes you want to download data for, as well as set the maximum number of bars to download for both history and chart. The expert advisor will handle the downloading process and provide progress updates on the Experts log.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mt4-history-loader-automated-forex-data-download-review/).
