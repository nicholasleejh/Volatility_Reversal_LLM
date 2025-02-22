# Volatility_Reversal_LLM
Goal: 

To fine-tune an LLM that can accurately classify volatility reversals by analysing daily news headlines, helping traders and investors make more informed decisions about managing risk and timing trades.

Volatility reversals are critical events in financial markets, often signaling significant changes in market sentiment and potential shifts in asset prices. Accurately identifying these reversals enables traders and analysts to anticipate sudden shifts in market direction, improving risk management and trading strategies. By identifying potential reversals, investors can optimize entry and exit points, reduce losses, and enhance returns. Additionally, accurate classification helps in developing algorithmic trading models that adapt to changing market conditions, ultimately leading to more resilient and efficient trading systems.

Rationale:

Traders and investors are constantly being bombarded with an endless stream of news and information, some of which hold contrarian or opposing views from the current market conditions. However, traders and investors do not usually act upon 1 piece of news alone, but rather the overall market sentiment. This is where the skill of the individual comes into play; knowing exactly when the current market sentiment has shifted, and what actions to take next. I want to identify moments when negative or contrarian views, which may have been wrong for a while, start to get serious market attention and actually cause a volatility reverse. I later define what constitutes volatility reversal below. Being a data scientist, instead of relying on years of trading experience, I shall create and fine-tune a model to emulate the knowledge of experts in the finance industry.

Folder navigation:
Data obtained from Refinitv Data Platform on 13/02/2025. Data is stored with the data folder.
Code is stored with the src folder.
