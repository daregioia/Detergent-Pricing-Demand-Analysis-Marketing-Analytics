# Detergent Pricing & Demand Analysis
Pricing, cannibalization, and competitive response analysis for P&G’s Tide detergent line.

🚀 Overview

This project analyzes scanner data from 86 Chicago stores to evaluate:
- Cannibalization between Tide 128 oz and Tide 64 oz
- Competitive interaction with Wisk 64 oz
- Demand elasticities under multiple model specifications
- Pricing strategy and profit optimization for Tide

All analysis is conducted in Python via Jupyter/Colab.

🛠️ Methods



Descriptive analysis: market shares, price statistics, price gaps

Demand estimation:
- Log-linear models for Tide 64 & Tide 128
- With: all prices, time trend, non-promoted weeks, fixed effects

Pricing & profitability:
- Base price & base volume calculations
- Profit impact of ±5% price changes
- Evaluation of optimal product-line pricing

  

🔍 Key Findings
- Evidence of internal cannibalization between Tide 64 oz and 128 oz
- Tide faces moderate competitive pressure from Wisk
- Demand elasticities improve substantially after controlling for promotions and store fixed effects
- Current pricing is close to—but not exactly—profit-maximizing; selective adjustments can increase total profit
