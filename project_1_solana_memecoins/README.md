**Project 1 — Solana Memecoin Market Intelligence**

**Overview**

This project analyzes memecoin trading activity on the Solana blockchain to determine whether observed trading volume reflects genuine market demand or short-term speculative behavior.

Rather than relying on raw volume alone, the analysis focuses on trader participation, token lifecycle behavior, and volume sustainability.

**Problem Statement**

Memecoin markets are often driven by hype, making it difficult to distinguish between organic adoption and speculative spikes. This project aims to identify which tokens exhibit sustained engagement versus short-lived interest.

**Data**
1. Solana DEX trade data

2. Token mint addresses

3. Trader wallet addresses

4. Trade timestamps and USD-denominated values

**Methodology**

1. Extracted on-chain DEX trade data using SQL

2. Aggregated trades into daily metrics (volume, unique traders)

3. Filtered for the most actively traded tokens

4. Analyzed token lifecycle trends and trader retention

5. Built an interactive dashboard for token-level comparison

**Key Insights**

1. The majority of trading volume is driven by brief speculative spikes

2. Only a small subset of tokens shows consistent trader participation

3. Sustained trader activity is a stronger signal of adoption than volume alone

**Tools**

SQL · Python · Streamlit · Solana on-chain data