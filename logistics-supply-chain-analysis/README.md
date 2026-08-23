# Logistics & Supply Chain Analysis

A Tableau dashboard analyzing global sales, shipping efficiency, and payment methods across international markets.

**Data:** Kaggle Raw dataset (global supply chain sales data).

## What it looks at
- Sales, order volume, and profit margin by country and market
- Yearly sales trends (2015–2018) by market segment
- Top and bottom performing products
- Shipping time by shipping mode and market
- Payment method distribution and order status breakdown

## Key insights
- Total global sales of roughly €3M with an overall profit margin sum of €2.795M across the dataset.
- The **United States led all markets** (€12.82M sales, 400K orders, 11.58% margin), followed by **Mexico** (€7.59M, 248K orders, 13.26% margin), **France** (€5.09M, 256K orders, 14.29% margin — the strongest margin of the top four), and **Germany** (€3.43M, 169K orders, 8.12% margin — the weakest of the top four, worth investigating further).
- Sales **peaked sharply in 2016** (399K sales, 2,041 customers) before declining through 2017–2018, a trend worth flagging for deeper analysis.
- **Perfect Fitness, Nike Men's Dri-FIT, and O'Brien Men's Field Stream** were the top three products by order count, while a distinct group of niche products (Merrell Women's, Ogio Race Golf, GoPro HERO3) sat at the very bottom with minimal volume.
- **Standard-class shipping was consistently the slowest** (8.43–10.39 days depending on market), while first and second class moved noticeably faster — a clear lever for improving customer experience.
- **DEBIT was the dominant payment method in Europe** (376K in sales), while the USCA market showed a more even split across payment types.

## Why this project
Sales, shipping, and payments aren't separate problems — they all shape the same customer experience. This dashboard was built to connect those three layers into one view, so slow shipping, payment friction, or underperforming products can be spotted and acted on together rather than in isolation.

**Tools:** Tableau

## Files in this folder
- `logistics-supply-chain-analysis.pdf` — Dashboard Screenshots
- `Logistics_supply_chain_analysis.xls` - Raw Data File from Kaggle
- `'logistics-supply-chain-analysis.pptx` — Presentation Slides
- `'Project_2` - Main Tableau Dashboard File
