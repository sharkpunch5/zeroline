![Image](logo.png)

![Image](https://img.shields.io/github/issues/sharkpunch5/zeroline) ![Image](https://img.shields.io/github/license/sharkpunch5/zeroline) ![Image](https://img.shields.io/badge/language-pinescript-blue) ![Image](https://img.shields.io/badge/platform-tradingview-blueviolet)

## Disclaimer
Trading Forex involves a risk of loss. Please consider carefully if such trading is appropriate for you. Past performance is not indicative of future results. Content on this site are for research and informational purposes only and do not constitute investment recommendations or advice.

## Description
This algorithm is designed to identify and trade trends in the foreign exchange (forex) market. It is constructed using a set of technical indicators that trigger trade entry and exit and uses money management to limit risk and maximise upside potential.

It has been developed and tested in Metatrader 4 and Trading View, this algorithm is written in pine script can be deployed as a strategy in the Trading View and used for back testing on any instrument that is available on the platform. 

Testing across the major pairs (USD, EUD, JPY, CHF, GBP, AUD, NZD) yields a *theoretical* annualized ROI of ~30% per annum with default configuration however it is critical to note that the performance will decline in practical application once rules are added to avoid the volatility associated news events and limit exposure.

This algorithm and script utilise the No Nonsense Forex (NNFX) trading methodology and has been developed using the TradingView Strategy Coding Series on YouTube, so a huge thank-you and full credit to the creators that content VP and Dillon Grech. For those new to this arena please ensure you consume all of the content and engage in the communities at the following links before attempting to use this tool.

* No Nonsense Forex - [Web](https://nononsenseforex.com/) / [YouTube](https://www.youtube.com/channel/UCc8IRYpgBr4NGbaQFnd2b-A) / [Discord](https://discord.gg/5TEY6h6)
* TradingView Strategy Coding Series - [YouTube](https://www.youtube.com/channel/UCl1a4qyx_HaodV0AN9ve46A) / [Discord](https://discord.gg/bxn7kMC)

## Installation

1) Sign-up and create a free Trading View account
2) Add the strategy to chart using either of the following options:
a) The Easy Way
b) The Hard(er) Way

## Usage


Example Strategy Tester Output
![Image](strategy_tester.png)

## Configuration


## Support
If you have questions message me on Discord @sharkpunch in either of the following servers
* [No Nonsense Forex](https://discord.gg/5TEY6h6)
* [The Trading Journal](https://discord.gg/bxn7kMC)

## Roadmap
* Add option for multiple exit indicators
* Combine Indicators to single on chart indicator
* Simplify/Improve on chart plotting
* Optimise indicator combiations to improve ROI!

## Known Issues
* Indicator/Strategy performance on Trading View  differs to the MT4 
* Trailing Stop Loss on order 2 is created at 1.5x ATR when trade is entered as opposed to being fixed until take profit on first order is hit, then moved to break even, then moved to 1.5 ATR only once price moves 2x ATR from entry price (platform limitation).
* Historical volume data for the 28 currency pairs on Trading View can occasionally chance depending on the time the stratey is loaded. (data quality issue)
* Results will vary based on broker used, all testing on both MT4 and TradingView has used historical data from [FXCM](https://www.fxcm.com/au/)

## Acknowledgements
