# PAX Multi TMA HMA 8 for MT5

Developer: Forex Robot Easy Team

Website: [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/pax-multi-tma-hma-8-mt5-review-strategy-insights/)

## Description

This code is a trading strategy based on the PAX Multi TMA HMA 8 indicator for MetaTrader 5. It calculates the TMA (Triangular Moving Average) and HMA (Hull Moving Average) indicators and generates trading signals based on their values.

## How it Works

1. The `CalculateTMA` function calculates the TMA based on the specified period. It sums the closing prices of the previous `period` bars and divides it by `period` to get the average.

2. The `CalculateHMA` function calculates the HMA based on the specified period. It uses a weighted moving average (WMA) to calculate the HMA. It first calculates two WMAs using different weights for the first half of the period, and then combines them to calculate the HMA.

3. The `GenerateTradingSignals` function compares the TMA and HMA values and determines the trading signal. If the TMA is greater than the HMA, it returns `OP_BUY` to enter a buy trade. Otherwise, it returns `OP_SELL` to enter a sell trade.

4. The `OnTick` function is the entry point of the program. It calculates the TMA and HMA values using a period of 8, and then generates the trading signal. If the signal is `OP_BUY`, it executes a buy trade. If the signal is `OP_SELL`, it executes a sell trade.

## Product Description

PAX Multi TMA HMA 8 for MT5 is a powerful trading strategy developed by the Forex Robot Easy Team. This strategy utilizes the Triangular Moving Average (TMA) and Hull Moving Average (HMA) indicators to generate accurate trading signals.

The TMA indicator calculates the average of the closing prices over a specified period, providing a smooth and reliable trend-following signal. On the other hand, the HMA indicator uses a weighted moving average approach to eliminate lag and provide more timely signals.

By combining these two indicators, PAX Multi TMA HMA 8 for MT5 identifies favorable trading opportunities and suggests whether to enter a buy or sell trade. This strategy is suitable for both beginner and experienced traders who seek a systematic and efficient approach to trading.

Please note that Forex Robot Easy is not the official developer of this product. We provide this sample code as a demonstration of the strategy described in this product. To find the official developer of PAX Multi TMA HMA 8 for MT5, please refer to the MQL5 platform.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/pax-multi-tma-hma-8-mt5-review-strategy-insights/).
