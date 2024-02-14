# SevenDaysEA Expert Advisor

## Table of Contents
- [Introduction](#introduction)
- [Input Parameters](#input-parameters)
- [Trading Strategy](#trading-strategy)
- [Installation](#installation)
- [Deinitialization](#deinitialization)
- [Disclaimer](#disclaimer)

## Introduction
This is the ReadMe file for the SevenDaysEA Expert Advisor, developed by the Forex Robot Easy Team. This Expert Advisor is designed to trade on the AUDCAD, AUDNZD, and NZDCAD currency pairs. It utilizes a fully automated grid system to execute trades.

For detailed reviews and trading results of this product, please visit the [SevenDaysEA Review](https://forexroboteasy.com/forex-robot-review/sevendaysea-review-automated-forex-software-for-audcad-audnzd-nzdcad/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Input Parameters
- `currencyPairs`: Specifies the currency pairs to trade. Default value: 'AUDCAD, AUDNZD, NZDCAD'
- `AUDCAD_set1` to `AUDCAD_set10`: Set-files for the AUDCAD currency pair
- `AUDNZD_set1` to `AUDNZD_set10`: Set-files for the AUDNZD currency pair
- `NZDCAD_set1` to `NZDCAD_set10`: Set-files for the NZDCAD currency pair

## Trading Strategy
The SevenDaysEA Expert Advisor implements a fully automated grid system. The code for the grid system is implemented in the `OnTick()` function. This function is called on every tick of the price data.

## Installation
To install the SevenDaysEA Expert Advisor on your MetaTrader 5 terminal, follow these steps:
1. Copy the SevenDaysEA.mq5 file to the 'Experts' folder of your MetaTrader 5 terminal.
2. Open the MetaTrader 5 terminal and navigate to the 'Navigator' panel.
3. Expand the 'Expert Advisors' section.
4. Locate the SevenDaysEA Expert Advisor and drag it onto the chart of the corresponding currency pair.
5. Adjust the input parameters as desired.
6. Click the 'Auto Trading' button in the toolbar to enable automated trading.

The Expert Advisor will now start executing trades based on the specified strategy.

## Deinitialization
The `OnDeinit()` function is called when the Expert Advisor is removed from the chart or the terminal is closed. You can add custom deinitialization code in this function if required.

## Disclaimer
The SevenDaysEA Expert Advisor is developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit the [SevenDaysEA Review](https://forexroboteasy.com/forex-robot-review/sevendaysea-review-automated-forex-software-for-audcad-audnzd-nzdcad/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.
