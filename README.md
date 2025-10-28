# On-Chain Market Analysis: The Impact of Whale Activity on Bitcoin and Ethereum Volatility

## Project Description

This project presents an in-depth analytical study of the relationship between whale activity (large investor transactions) and the market behavior of Bitcoin and Ethereum throughout 2024–2025. It integrates on-chain metrics, price dynamics, volatility trends, and whale transaction share in market capitalization to identify meaningful patterns and potential early signals in the crypto markets.

## About Data

The dataset was sourced using the Santiment API, which provides access to on-chain data, user activity metrics, and market analytics for crypto assets. The data was saved as a CSV file.

## Dataset Column Descriptions

* date - Date of the recorded metrics
* coin_id -	Cryptocurrency identifier (e.g., bitcoin, ethereum)
* price_usd -	Current price in USD
* daily_active_addresses -	Number of unique addresses active on that day
* transaction_volume - Total on-chain volume of coins moved
* marketcap_usd -	Market capitalization (price × circulating supply)
* whale_trans_count_100k -	Number of transactions > $100,000 USD
* whale_trans_volume_100k -	Total volume of transactions > $100,000 USD
* whale_trans_count_1m - Number of transactions > $1,000,000 USD
* whale_trans_volume_1m -	Total volume of transactions > $1,000,000 USD

## Objective

Explore the impact of large capital flows (≥100K and ≥1M USD transactions) on price fluctuations and volatility.
Compare Bitcoin and Ethereum based on structured on-chain data.
Visualize weekly seasonality, price correlation, and the market share driven by whale movements.

## Tech Stack

Python, Pandas, Plotly, Matplotlib, Seaborn, Santiment API (source of on-chain metrics for BTC & ETH).

## Key Analytical Questions 

1. How do Bitcoin and Ethereum price dynamics compare across 2024–2025?
2. Is there a positive correlation between BTC and ETH?
3. How are the main market metrics related to each other?
4. Which asset is more volatile and which one is more stable?
5. What share of the market is moved by whale activity?
6. Are there weekly or monthly cycles in whale behavior?
7. Does heightened whale activity precede price volatility?
8. How has the volume of large transactions evolved in 2025 vs 2024?

## Key Insights

* Whale Activity Drops on Weekends
The number of big investor transactions becomes smaller on Saturdays and Sundays. This is a common pattern in crypto markets — most activity happens during weekdays.

* More Whale Transactions in 2025
In 2025, the amount of large transactions grew compared to 2024. This shows that more big players (like institutions or wealthy investors) entered the market.

* Ethereum Reacts More to Whale Activity
Ethereum’s price changes more strongly when whales are active. The highest whale activity days often match with strong price moves in ETH.

* Bitcoin Is More Stable Than Ethereum
Bitcoin usually changes less in price (2–4% most of the time), while Ethereum has more price spikes — sometimes over 6–7%. This means ETH is more volatile and risky.

* Price Spikes Happen at the Same Time
Both Bitcoin and Ethereum often show high volatility on the same days. This means they are both affected by the same events — like news or large investor moves.

* Similar Price Trends in 2024–2025
The price of Bitcoin and Ethereum moved in the same direction most of the time. Ethereum followed Bitcoin’s trend but with stronger ups and downs.

* Whale Influence in the Market
Bitcoin has a larger share of whale transactions in its market cap, but Ethereum’s price is more sensitive to them. Even a small change in ETH whale activity can move the price.




