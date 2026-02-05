Trader Performance vs Market Sentiment
Objective

The goal of this project is to understand how Bitcoin market sentiment (Fear and Greed) affects trader behavior and performance on the Hyperliquid platform. The analysis focuses on identifying patterns that can help traders make better decisions under different market conditions.

Datasets

Historical trader data from Hyperliquid

Bitcoin Fear & Greed Index

Note: Due to the large size of the datasets, raw data files are not included in this repository.

Methodology

Trade-level data was cleaned and converted to a daily format

Market sentiment data was aligned with trader activity using the date field

Daily trader metrics such as total PnL, number of trades, average trade size, and long/short ratio were calculated

Trader performance and behavior were compared across Fear and Greed market conditions

Traders were grouped into segments based on trading frequency and trade size to observe behavioral differences

Key Insights

Traders generally perform better during Greed periods, while Fear periods are associated with lower profitability and higher uncertainty.

Traders who trade frequently or use larger trade sizes tend to benefit in Greed markets but experience larger losses during Fear.

A clear shift in behavior is observed: traders take more long positions during Greed and become more defensive during Fear.

Strategy Recommendations

During Fear market conditions, traders should reduce their trade size and avoid overtrading to manage downside risk.

During Greed market conditions, increased trading activity should be limited to experienced or frequent traders, while others should remain conservative.

How to Run

Open the Assignment.ipynb notebook

Install the required Python libraries (pandas, matplotlib)

Run the notebook cells in order to reproduce the analysis
