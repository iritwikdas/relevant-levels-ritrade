# Relevant Levels — Ritrade
### A Smart Price Level Indicator for TradingView | PineScript v5
 
[![TradingView](https://img.shields.io/badge/TradingView-Published-blue?logo=tradingview)](https://www.tradingview.com/script/LJ1VaYhH-Relevant-Levels-Ritrade/)
[![PineScript](https://img.shields.io/badge/PineScript-v5-green)](https://www.tradingview.com/pine-script-docs/en/v5/Introduction.html)
 
---
 
## Overview
 
**Relevant Levels** plots the most actionable price levels — Daily, Weekly, and Monthly Highs, Lows, and Opens — with a focus on keeping your chart clean and readable. Most level indicators clutter the chart with overlapping labels and lines drawn through live price action. This indicator solves both problems.
 
Designed for traders who use multi-timeframe key levels as part of their analysis workflow.
 
---
 
## Key Features
 
### Smart Overlap Prevention
When two levels share the exact same price (e.g., Previous Day High coincides with Weekly High), the indicator automatically offsets the second line to the right so both remain visible side-by-side. No more stacked, unreadable labels.
 
### Future Offset
All lines are projected into the future — drawn to the right of the current bar — so they never clutter your active price action or interfere with your chart analysis.
 
### Origin Trace Lines
Faint dotted grey lines connect each floating label back to the exact candle where that High, Low, or Open was formed. This makes it immediately clear *when* a level was created, not just *where* it sits.
 
### Exact Timing
Trace lines use precise time coordinates to anchor to the specific swing high or low candle, rather than approximating by bar count.
 
---
 
## Included Levels
 
| Label | Description |
|-------|-------------|
| PDH   | Previous Day High |
| PDL   | Previous Day Low |
| PWH   | Previous Week High |
| PWL   | Previous Week Low |
| DO    | Daily Open |
| WO    | Weekly Open |
| MO    | Monthly Open |
 
All levels are individually toggleable via the Settings panel.
 
---
 
## Settings
 
| Parameter | Description |
|-----------|-------------|
| Line Colors | Customize color for each level individually |
| Offset Distance | Controls how far right the lines are projected from the current bar |
| Line Length | Adjusts the horizontal length of each level line |
| Overlap Gap | Sets the vertical gap between lines when two levels share the same price |
 
---
 
## Usage
 
1. Open TradingView and navigate to the **Indicators** panel
2. Search for **"Relevant Levels Ritrade"** under Public Scripts
3. Add to chart — works on any ticker and any timeframe
4. Customize via the Settings panel to match your chart style
Alternatively, view and add the published script directly:
[tradingview.com/script/LJ1VaYhH](https://www.tradingview.com/script/LJ1VaYhH-Relevant-Levels-Ritrade/)
 
---
 
## Preview
 
 <img width="1097" height="483" alt="Screenshot 2026-04-18 at 6 13 14 AM" src="https://github.com/user-attachments/assets/e51a7c31-12ef-43c3-ab35-594bacb91ac3" />
 
---
 
## Author
 
**Ritwik Das**
Quantitative Trader | Algorithmic Systems Developer
[LinkedIn](https://linkedin.com/in/iritwikdas) · [TradingView](https://www.tradingview.com/u/Ritrade/)
 
---
 
## License
 
This script is published under the [Mozilla Public License 2.0](https://mozilla.org/MPL/2.0/).
Feel free to use, study, and build upon it with attribution.

