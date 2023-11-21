// ReadMe File for Trend Line GRID mt4 EA

// This code is an Expert Advisor (EA) for MetaTrader 4 platform (mt4). It is designed to automate trading based on price deviation and manual trades with the use of a grid of orders. This EA is developed by the Forex Robot Easy Team and can be found on their website forexroboteasy.com. For detailed reviews and trading results of this product, please visit https://forexroboteasy.com/forex-robot-review/review-trend-line-grid-mt4-real-results-and-download/

// Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5 website.

// This EA has several input parameters that can be modified as per user's preference:
// - AutoTrading: Enable or disable auto trading
// - CloseGrid: Close the entire grid of orders
// - ManualMode: Enable or disable manual mode for accompanying and resolving manual trades
// - TradeSize: Size of the trade

// The EA works by checking if auto trading is enabled and if the price deviates. If the price deviates, it opens the first order and builds a grid of orders. If manual mode is enabled, it accompanies and resolves manual trades into profit. The entire grid can be closed if required.

// The code is structured into several functions:
// - OnInit(): Initialization function called when EA is loaded
// - OnTick(): Main function that is executed on every tick of the market
// - PriceDeviation(): Function to check if the price deviates
// - OpenOrder(): Function to open the first order
// - BuildGrid(): Function to build a grid of orders
// - CloseUnprofitableOrders(): Function to close unprofitable orders
// - AccompanyManualTrades(): Function to accompany and resolve manual trades
// - CloseAllOrders(): Function to close all orders

// The code is meant to be customized as per user's strategy and trading requirements. It is important to backtest and optimize the EA before using it on a live trading account.
