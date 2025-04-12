# TQQQ vs QQQ: Automated Investment Performance Analysis using Yahoo Finance API


# Project Title
  
  TQQQ vs QQQ: Automated Investment Performance Analysis using Yahoo Finance API

# Project Summary

  This Power BI dashboard provides a dynamic and visual comparison of the investment performance of TQQQ and QQQ, leveraging real-time data extracted from   
  Yahoo Finance via Python API integration. It enables investors to assess the impact of leveraged ETFs over different periods using key return metrics and 
  dollar-cost averaging simulations.

# Problem Statement

  Retail and institutional investors often struggle to evaluate the long-term risks and returns of leveraged ETFs compared to their non-leveraged counterparts. 
  This project aims to build an automated dashboard that offers:

  - A direct comparison of TQQQ (ProShares UltraPro QQQ) vs QQQ (Invesco QQQ Trust)
  - Insights into annual return performance
  - Dollar-Cost Averaging (DCA) outcomes over multiple time frames
  - Interactive tools for investment scenario analysis

# Dataset Details

    1. Source: Yahoo Finance
    
    2. API Used: yfinance Python library
    
    3. Assets Analyzed:

       - QQQ: Tracks the Nasdaq-100 index (non-leveraged ETF)
       - TQQQ: A 3x leveraged ETF aiming to triple the daily performance of the Nasdaq-100
       
    4. Data Span: Covers 10+ years of daily prices and returns
    
    5. Automation: Dashboard refreshes data automatically on connection

# Dashboard Insights

  - Page1: 5-Year and 10-Year Total Return Comparison
    
        - Line graphs showing performance divergence between TQQQ and QQQ
        - Highlights volatility and compounding effect of leverage
    
    <img width="754" alt="image" src="https://github.com/user-attachments/assets/c70ea51f-0ae4-400f-a462-4f01305e0157" />


  - Page2: Annual Return Breakdown (Bar Chart):

         - Year-wise return comparison from 2010 to 2025
         - Green = positive return, Red = negative return
         - Emphasizes TQQQ’s sharp gains in bullish years and heavy losses in bearish ones

  - Page3: Dollar-Cost Averaging (DCA) Calculator:

         - Enter monthly investment amount
         - See how much the investment would grow in TQQQ vs QQQ over 5 years
         - Displayed in both graph and table view

  - Page4: Rolling DCA Results (5-Year Windows):

         - Tracks cumulative investment growth over multiple rolling periods
         - Assesses risk/reward from different investment starting points

# Key Findings

- TQQQ significantly outperforms QQQ in strong bull markets (e.g., 2019–2021)
- Drawdowns are severe in bear markets for TQQQ (e.g., -79% in 2022)
- DCA in TQQQ is more volatile, but can yield higher long-term returns if timed right
- QQQ provides more stable, lower-risk returns, suitable for conservative investors

# Actionable Insights
- Use the DCA simulator to assess hypothetical investment returns
- For long-term consistent investors, QQQ offers smoother ride
- For risk-tolerant investors, TQQQ offers amplified gains and losses — timing matters
- Portfolio strategies should weigh both instruments based on market sentiment
