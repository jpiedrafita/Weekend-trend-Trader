# Weekend Trend Trader Pine Script Collection for TradingView

This repository contains a collection of Pine Script files designed for use on TradingView. Each script serves a specific function, from filtering index trends to analyzing resistance levels and implementing trading overlays.

The two main scrits [weekend_trend_trader_overlay](./weekend_trend_trader_overlay.pine) and [weekend_trend_trader_ribbon](./weekend_trend_trader_ribbon.pine) hold all the required indicators for the [Weekend Trend Trader](https://www.amazon.es/Weekend-Trend-Trader-English-Radge-ebook/dp/B00F4P0OWA) Strategy written by Nick Radge.

## Scripts Description

### Index Trend Filter
- **File**: [`index_trrend_filter.pine`](./index_trend_filter.pine)
- **Description**: This script provides an index trend filter which plots a histogram indicating the trend direction based on a simple moving average (SMA) of the index price.
- **Usage**: Useful for identifying bullish or bearish trends in a selected index (e.g., NASDAQ:NDX).

### Resistance Calculation
- **File**: [`resinstance.pine`](./resistance.pine)
- **Description**: Calculates and plots the highest price level over the last 20 periods, providing a visual representation of resistance levels.
- **Usage**: Can be used to identify potential breakouts in the price chart of an asset.

### Weekend Trend Trader Overlay
- **File**: [`weekend_trend_trader_overlay.pine`](./weekend_trend_trader_overlay.pine)
- **Description**: Combines trend analysis with dynamic stop loss calculation, adjusting the stop loss based on the trend and a specified start date.
- **Usage**: Helps to manage the risk by dynamically adjusting stop loss levels based on the prevailing market conditions. **Hint**: drag and drop the initial date to adjust the stop loss start date.

### Weekend Trend Trader Ribbon
- **File**: [`weekend_trend_trader_ribbon.pine`](./weekend_trend_trader_ribbon.pine)
- **Description**: This script includes an index filter ribbon and a Rate of Change (ROC) indicator set to detect 30% changes over 20 periods.
- **Usage**: Useful for traders looking to gauge significant price movements and adjust their strategies accordingly.

## Installation
To use these scripts:
1. Open your TradingView chart.
2. Click on "Pine Editor" located at the bottom of the TradingView interface.
3. Copy and paste the content of each `.pine` file into the Pine Editor.
4. Click on "Add to Chart" to apply the script.

## Author
- Jorge Piedrafita

## Contributions
Contributions are welcome. Please fork the repository and submit a pull request with your enhancements.

## License
This project is open-source and available under the MIT License.
