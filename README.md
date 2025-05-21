# AI Bank Predictor: Forecasting Bond Holdings Activity for 2025 in US Banks

The Banking Ranking System project leverages FDIC financial data (2010–2024) to predict banks' likelihood of increasing fixed income securities purchases in 2025 using an LSTM model. 
It fetches and validates data for 44 banks, focusing on metrics like bond holdings (SCHTMRES, SC), liquidity (CHBAL/ASSET), and capital ratios (IDT1CER). 
The system generates scores (0–8) to rank banks, visualized via a bar chart of top 10 banks with uncertainty (historical score volatility) and a box plot of liquidity-to-assets ratios. 
Key findings highlight Green Dot Bank (~6.73), Jonesboro State Bank (~6.63), and United Bank (~6.17) as top targets for bond trading due to high scores and low uncertainty.
Recommendations prioritize outreach to these banks while monitoring high-uncertainty ones like XD Bank. 
Improvements include refining uncertainty estimation, handling missing data, and enhancing visualizations for strategic impact.
