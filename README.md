[Setup](https://github.com/2LV/tradingview-indicators?tab=readme-ov-file#setup) • [Disclaimer](https://github.com/2LV/tradingview-indicators?tab=readme-ov-file#disclaimer) • [License](https://github.com/2LV/tradingview-indicators?tab=readme-ov-file#license) <img align="right" src="https://github.com/2LV/Tradingview-Indicators/assets/70970973/74846972-8cdd-491e-9d35-272fe0a8167d" alt="Pinescript Logo" width="290" height="182.31" /> 

A collections of different Tradingview indicators (and their corresponding trading strategies) and strategiesbuilt in Pinescript V5. All indicators on this repository are up to date, but Tradingview indicators can be behind on updates so please make sure to use the most updated indicator for the most accurate results. Please contact me with suggestions for new indicators/strategies/changes

<br />

## [Institutional Supply & Demand Zones](https://github.com/2LV/Tradingview-Indicators/blob/main/indicators/Institutional%20Supply%20%26%20Demand%20Zones)
This indicator aims to identify price levels where institutional investors have positioned their buy or sell orders. These buy orders establish "demand zones," while sell orders create "supply zones." Identifying these zones enables us to anticipate potential reversals in price trends, allowing us to profitably engage in these significant market movements alongside major institutions. These zones are formed when price action goes from balanced to imbalanced. These zones are based on orders. Unlike standard support and resistance levels, when price breaks below a demand zone or above a supply zone, these zones disappear from the chart. Supply is formed by a green candle followed by a major red candle that is at least double the size of previous green candle. The zone is then charted from the open of the green candle to the highest point in the candle. Vice versa for a demand zone (red candle into green candle). Typically when a zone is retested multiple times, it will have a higher chance of breaking as more and more orders are being filled. Add it to your chart [here](https://www.tradingview.com/script/eAO9uAu5-Institutional-Supply-and-Demand-Zones/)

### Features

1. Zone Difference Scale: The scale of how much a candle needs to be larger than a previous to be considered a zone
2. Zone Extension: How much to extend zones to the right of latest bar in bars
3. Display Lower Timeframe Zones: A feature to attempt to display zones that are formed on a lower timeframe than the current one (ex. 30m zone on 4h chart)
4. Display Text/Display High/Low: Whether to or not to display the tops and bottoms of a zone as text (ie. Top: 4000.00 Bottom: 3900.00)

### How to trade

First, make sure you are trading an institutionally traded instruments. Second, look for an exaggerated volume spike in suppy or demand. This is the first indication of a potential reversal, also known as volume confirmation. After a confirmation appears, we need to make sure that it is enough to cause a reversal in the trend by waiting for a trend change confirmation. There are multiple ways to confirm a trend change: ChoCH, trendline break, BOS, etc.

![image](https://github.com/2LV/Tradingview-Indicators/assets/70970973/3b0c8719-e79e-4677-999f-8f4400868a15)

## [Reversal Pivot Points](https://github.com/2LV/Tradingview-Indicators/blob/main/indicators/Reversal%20Pivot%20Points) 
This indicator aims to identify price levels where price action has quickly reversed from. These "pivots" establish major levels where major liquidity is located. Unlike traditional support and resistance levels, when price breaks below or above a pivot, these pivots disappear from the chart. Add it to your chart [here](https://www.tradingview.com/script/OGeG7pyt-Reversal-Pivot-Points/)

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

1. Pivots can be traded to or from. The stock market (market makers) will tend to "chase" liquidity in order to fill orders at better averages. This allows us retail traders to to participate alongside these moves to these pivots. Once price action hits a pivot, it can do two things: break the pivot and continue or bounce off it. We can participate alongside these bounces after confirmation of a reversal (doji, volume, etc). These bounce plays are high risk as it's generally 50-50, but the risk to reward is also very high, making them very valuable to take.
2. Typically, the market is a fluid environment and should be "natural" so perfect things (manmade therefore filled with liquidity) should not occur. We can expect these perfect tops and bottoms, referred to as "PDT/PDB", to break as they are not natural and have heavy liquidity on and above/below them. We can trade to these levels and expect them to break if price action comes near them again. 

![image](https://github.com/2LV/Tradingview-Indicators/assets/70970973/8f823bf0-69f7-4c27-a726-967af4ca3bfd)

## [Abnormal Volume Scanner](https://github.com/2LV/Tradingview-Indicators/blob/main/indicators/Abnormal%20Volume%20Scanner)
This indicator aims to revolutionize and simplify volume analysis through multiple different pattern recognition methods. Volume is the first piece of evidence in any moves in price action and retail traders must understand and analyze volume to properly assess future price action. Volume can be paired with a variety of different strategies and indicators for maximum efficiency. (Warning: It is recommended that you set the chart bottom margin to **0%** to remove the space between the bottom of the chart and volume)

### Features

1. Color Based On Previous Volume: Base volume color off the previous volume bar instead of OHLC values
2. Volume MA: Basic moving average for X volume bars in the past
3. Abnormal Volume Spike: Major spikes of X multiplier (based off "Abnormal Volume multiplier") in volume compared to X volume bars in the past (based off "Tracked Candles")
4. Abnormal Volume Loss: Major losses of X multiplier (based off "Abnormal Volume multiplier") in volume compared to X volume bars in the past (based off "Tracked Candles")
5. Plot Shapes On Abnormal: Plots a shape on any abnormal volume bars (change color and shape under style tab. Feature disables color bar changes of abnormal volume)
6. Tracked Candles: The average of X candles in the past
7. Abnormal Volume Multiplier: X amount multiplier necessary to be considered abnormal (e.g., 0.3 means 1.3x multiplier for abnormal spike or 0.7x for abnormal loss)
8. Increasing/Decreasing Volume: Creates a trendline from the high/low
9. Consecutive Candle Requirement: How many candles are required in a row to be considered increasing/decreasing volume
10. Minimum/Maximum Volume Change: Minimum/maximum amount of change in volume per candle allowed (e.g., 0.5 limits to 50% more/less in change of volume per candle, 0.1 needs 10% more/less in change of volume per candle)
    
### How to trade

1. One of the most basic ways of trading volume is playing breakouts with volume/momentum. A breakout can be any type of resistance/support (trendlines, pivots, etc). We will wait for a breakout pattern to form, then enter whichever direction abnormal volume appears in after a breakout. 
2. We can also use volume to assess the strength of a move. For example, if a move up has decreasing volume alongside smaller candlesticks, we can expect and enter a pullback after proper confirmation (volume spike, reversal candle, momentum, etc). Increasing volume alongside decreasing momentum/candlestick size can mean that there are volume increases in the opposite side, allowing us to expect potential reversals. We can also use volume to assess the strength of a pullback -- if a pullback is backed by very strong momentum and volume, we can expect the pullback to turn into a potential reversal.
3. Decreasing volume typically does not last and can "break out" in a sense. For example, if there are multiple candles that are weak and decreasing in volume, we can expect there to be a spike in volume coming and enter whichever direction this spike goes.
4. Sudden decreases in volume can mean temporary accumulation/consolidation, allowing us to anticipate potential continuation.

![image](https://github.com/2LV/Tradingview-Indicators/assets/70970973/5e717e0a-c7d9-4b38-8d2b-793290eb380d)

## [Multiple Moving Average](https://github.com/2LV/Tradingview-Indicators/blob/main/indicators/Multiple%20Moving%20Averages) 
A simple indicator to plot 5 different types of moving averages (SMA, EMA, WMA, HMA, RMA) and VWAP in different colors.

![image](https://github.com/2LV/Tradingview-Indicators/assets/70970973/30bdda4a-4369-4510-b472-b083f6ece1d8)

# Setup

1. Open "Pine Editor"
2. Open the dropdown called "Open"
3. Click "New indicator"
4. Paste the script in and press "Add to chart"

![image](https://github.com/8pz/tradingview-scripts/assets/70970973/b0e9d1bf-55da-4ab4-a3df-6396d7b980a4)

# Disclaimer

The trading indicators and strategies shared here are for educational purposes only. They do not constitute financial advice or recommendations. Trading carries risks, and past performance is not indicative of future results. The creators and contributors of the project are not responsible for any losses from recommendations from any indicators under this project. Traders should exercise caution and conduct their own research before making any trading decisions.

# License

All scripts under project are licensed under [**CC BY-NC 4.0**](http://creativecommons.org/licenses/by-nc/4.0/)

Commercial reuse is **strictly prohibited**

- discord @ nqmicro
- telegram @ [nqmicro](https://t.me/nqmicro)
- email @ 123781023@proton.me
