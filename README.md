# stock-market-anlalysis-VWAP
# Calculating VWAP
VWAP is the average price a security has traded at throughout the day, based on both volume and price and is important because it provides traders with insight into both the trend and value of a security.

The VWAP calculation is performed by charting software and displays an overlay on the chart representing the calculations. This display takes the form of a line, similar to other moving averages. How that line is calculated is as follows:


Choose your time frame (tick chart, 1 minute, 5 minutes, etc.)
Calculate the typical price for the first period (and all periods in the day following). Typical price is attained by taking adding the high, low and close, and dividing by three: (H+L+C)/3
Multiply this typical price by the volume for that period. This will give you a value called TPV.
Keep a running total of the TPV values, called cumulative-TPV. This is attained by continually adding the most recent TPV to the prior values (except for the first period, since there will be no prior value). This figure should get larger as the day progresses.
Keep a running total of cumulative volume. Do this by continually adding the most recent volume to the prior volume. This number should also get larger as the day progresses.
Calculate VWAP with your information: [cumulative TPV ÷ cumulative volume]. This will provide a volume weighted average price for each period and will provide the data to create the flowing line that overlays the price data on the chart.
