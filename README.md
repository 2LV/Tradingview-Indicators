[Setup](https://github.com/8pz/tradingview-indicators?tab=readme-ov-file#setup) • [Disclaimer](https://github.com/8pz/tradingview-indicators?tab=readme-ov-file#disclaimer) • [License](https://github.com/8pz/tradingview-indicators?tab=readme-ov-file#license)

## [Institutional Supply & Demand Zones](https://github.com/8pz/Tradingview-Indicators/blob/main/scripts/Institutional%20Supply%20%26%20Demand%20Zones)
This indicator aims to identify price levels where institutional investors have positioned their buy or sell orders. These buy orders establish "demand zones," while sell orders create "supply zones." Identifying these zones enables us to anticipate potential reversals in price trends, allowing us to profitably engage in these significant market movements alongside major institutions. These zones are formed when price action goes from balanced to imbalanced. These zones are based on orders. Unlike standard support and resistance levels, when price breaks below a demand zone or above a supply zone, these zones disappear from the chart. Supply is formed by a green candle followed by a major red candle that is at least double the size of previous green candle. The zone is then charted from the open of the green candle to the highest point in the candle. Vice versa for a demand zone (red candle into green candle). Add it to your chart [here](https://www.tradingview.com/script/eAO9uAu5-Institutional-Supply-and-Demand-Zones/)

### Features

1. Zone Difference Scale: The scale of how much a candle needs to be larger than a previous to be considered a zone
2. Zone Extension: How much to extend zones to the right of latest bar in bars
3. Display Lower Timeframe Zones: A feature to attempt to display zones that are formed on a lower timeframe than the current one (ex. 30m zone on 4h chart)
4. Display Text/Display High/Low: Whether to or not to display the tops and bottoms of a zone as text (ie. Top: 4000.00 Bottom: 3900.00)

### How to trade
1. Look for a volume spike in a zone
2. A trend change out of the zone (trendline break, ChoCh, etc)

![image](https://github.com/2LV/Tradingview-Indicators/assets/70970973/3b0c8719-e79e-4677-999f-8f4400868a15)

## [Reversal Pivot Points](https://github.com/8pz/tradingview-indicators/blob/main/scripts/Reversal%20Pivot%20Points) 
This indicator aims to identify price levels where price action has quickly reversed from. These "pivots" establish major levels where major liquidity is located. Unlike standard support and resistance levels, when price breaks below or above a pivot, these pivots disappear from the chart. Comes with various customization features built to fit all. Add it to your chart [here](https://www.tradingview.com/script/OGeG7pyt-Reversal-Pivot-Points/)

### Features
1. Pivot Timeframe: Identify and plot pivots from one specific timeframe and see it from all lower timeframes
2. Pivot left/right bar limit: A feature aimed at preventing false pivots identification
3. Remove On Close (ROC): Feature to only remove pivots once price close under it
4. ROC Timeframe: The timeframe the script uses to determine if the candle closed under the level
5. Wait For Close: Will only remove the pivot after the current candle closes
6. Line Extension Type: The extension of the line. None - extends line to current time, left - only extends line to the left, right - only extends line to the right, both - extends line both directions
7. Line Offset: How much to offset (in bars) the line and label from the current candle
8. Line Type: The style of line when plotted. Solid (─), dotted (┈), dashed (╌), arrow left (←), arrow right (→), arrows both (↔)
9. Display Level: Whether to or not to display the price of the pivot
10. Display Perfect Level: Whether to or not to display levels where price perfectly rejected off of
11. Alerts: Creates an alert when a level has been crossed

### How to trade

1. Pivots can be traded to or from. The stock market (market makers) will tend to "chase" liquidity in order to fill orders at better averages. This allows us retail traders to to participate alongside these moves to these pivots. Once price action hits a pivot, it can do two things: break the pivot and continue or bounce off it. We can participate alongside these bounces after confirmation of a reversal (doji, volume, etc). These bounce plays are high risk as it's generally 50-50, but the risk to reward is typically also very high, making them very valuable to take.
2. Typically, the market is a fluid environment and should be "natural," so perfect things (manmade and filled with liquidity) shouldn't occur. With this knowledge, we can expect these "PDT/PDB" to break as they are not natural and have heavy liquidity on and above/below them. We can trade to these levels and expect them to break if price action comes near them again. 

![image](https://github.com/2LV/Tradingview-Indicators/assets/70970973/8f823bf0-69f7-4c27-a726-967af4ca3bfd)

## [Multiple Moving Average](https://github.com/8pz/tradingview-indicators/blob/main/scripts/Multiple%20Moving%20Averages) 
A simple indicator to plot 5 different types of moving averages (SMA, EMA, WMA, HMA, RMA) and VWAP in different colors.

![image](https://github.com/2LV/Tradingview-Indicators/assets/70970973/30bdda4a-4369-4510-b472-b083f6ece1d8)

# Setup

1. Open "Pine Editor"
2. Open the dropdown called "Open"
3. Click "New indicator"
4. Paste the script in and press "Add to chart"

![image](https://github.com/8pz/tradingview-scripts/assets/70970973/b0e9d1bf-55da-4ab4-a3df-6396d7b980a4)

# Disclaimer

The trading strategies and indicators shared here are for educational purposes only. They do not constitute financial advice or recommendations. Trading carries risks, and past performance is not indicative of future results. Traders should exercise caution and conduct their own research before making any trading decisions.

# License

All scripts under project are licensed under [**CC NY-BC 4.0**](http://creativecommons.org/licenses/by-nc/4.0/)

Commercial reuse is **strictly prohibited**

- discord @ nqmini
- telegram @ [nqmicro](https://t.me/nqmicro)
- email @ 123781023@proton.me
