# BrightCart E-Commerce Profitability Analysis

## Overview
BrightCart is an e-commerce company selling across 8 product categories and 4 sales channels. Revenue was growing, but it wasn't clear which parts of the business actually made money. This project analyzes profitability after product costs, platform fees and returns, and recommends where to cut marketing spend.

## Business Questions
1. Which categories have the best and worst margins, and what drives them?
2. Which sales channels are profitable after platform fees?
3. What is the return rate, and how much revenue is lost to returns?
4. What is the ROAS (return on ad spend) for each ad platform?
5. If marketing budget is cut by 20%, where should the cut be made?

## Datasets
- **Order transactions:** orders, revenue, channel, returns
- **Product catalog:** product categories and costs
- **Marketing spend:** monthly ad spend by platform

## Tools
Power BI, Python, Excel

## Approach
- Combined the three datasets and calculated margin, channel profit after fees, return rate and ROAS
- Compared categories, channels and platforms to see which delivered the most and least profit relative to cost
- Built a 3-page Power BI report: Home, Channel and Recommendation

## Key Findings
- Profitability varied across the 8 product categories once product costs were taken into account, showing that high sales do not always mean high margin.
- Sales channels differed in how much profit they kept after platform fees, so revenue alone gave a misleading picture of channel performance.
- Returned orders reduced revenue and profit, making return rate an important factor when judging categories and channels.
- Ad platforms differed in return on ad spend (ROAS), with some delivering far more return per unit spent than others.

## Recommendation
Apply the 20% marketing budget cut to the platforms with the lowest return on ad spend, and protect the budget of the platforms and channels that deliver the highest profit relative to their cost.

## Dashboard
<img width="960" height="537" alt="image" src="https://github.com/user-attachments/assets/370cedcd-19f7-4c6a-9d4b-3dbe278437b5" />

## Files
- `BrightCart_Report.pbix`: Power BI report
- `data/`: datasets used
