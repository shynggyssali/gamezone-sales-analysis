# Gamezone Sales Analysis (2019 - Early 2021)

## Project Background

This project analyzes transactional data from an [Gamezone Orders Dataset](https://docs.google.com/spreadsheets/d/1uVlg4efe6QtUmYhyOk6lDNK72H6r-0je/edit?gid=1148435386#gid=1148435386) that operated between 2019 and 2021. The company operates in the e-commerce industry, selling a variety of products to customers across multiple countries via an online platform. The business model is centered on direct-to-consumer sales.

The power of Excel was used to inspect, clean, and analyze the data for this project, and the issues/insights log can be found in the `gamezone-orders-data.xlsx` file.
An interactive Power BI dashboard can be found in the `gamezone-dashboard.pbix` file.

## Data Structure

The dataset consists of two tables, `orders` & `region`, with the following columns:

- **USER_ID:** Unique identifier for each customer.
- **ORDER_ID:** Unique identifier for each transaction.
- **PURCHASE_TS:** Timestamp of when the purchase was made.
- **SHIP_TS:** Timestamp of when the order was shipped.
- **PRODUCT_NAME:** Name or description of the purchased product.
- **PRODUCT_ID:** Unique identifier for each product.
- **USD_PRICE:** Price of the product in USD.
- **PURCHASE_PLATFORM:** Channel through which the purchase was made (web / mobile app).
- **MARKETING_CHANNEL:** Source of customer acquisition or traffic (e.g., email, social media, direct).
- **ACCOUNT_CREATION_METHOD:** Method used by the customer to create their account (e.g., mobile, tablet, desktop).
- **COUNTRY_CODE:** Country associated with the customer or transaction.
- **REGION:** Geographical region corresponding to each country code (e.g., NA, EMEA).

## Executive Summary

### Overview of Findings

The analysis reveals a total sales revenue of approximately $6.15 million with an average order value of $282.17 from January 2019 to February 2021. Revenue shows steady growth from early 2019, followed by a sharp increase starting in early 2020, peaking close to $550K per month in late 2020. Product-level analysis indicates dynamic competition among top performers, with the 27in 4K gaming monitor, Nintendo Switch, and Sony PlayStation 5 Bundle consistently generating the highest monthly revenues. No single product dominated consistently, but revenue spikes align with certain product surges, particularly in late 2020.


## Insights Deep Dive

- **Revenue grew from $100k per month in January 2019 to ~$550K in December 2020, with fluctuations.**
  - Steady growth from January 2019 ($100K) to December 2019 ($180K).
  - Dips to ~$110K in January 2020, followed by a rapid growth peaking close to $550K per month in late 2020.
  - Declines sharply in early 2021, falling to $288K in February and $248K in March, indicating a potential post-peak slowdown or seasonal drop.
- **Product insights:** The peak in overall monthly revenue during late 2020 aligns with simultaneous surges in sales across the top three products — 27in 4K Gaming Monitor, Acer Nitro V Gaming Laptop, and Sony PlayStation 5 Bundle. This indicates that the revenue spike was not driven by a single breakout product but rather a converging surge in demand across multiple high-performing items, possibly due to seasonal promotions, product launches, or increased consumer spending during that period.


## Recommendations

Based on the insights and findings above, we recommend the following to the marketing and operations teams:

- **Anticipate post-peak slowdowns.** Prepare for potential revenue drops in Q1 by adjusting marketing spend and inventory levels. Consider running off-season campaigns to maintain engagement.
- **Review long-tail products with low sales volume.** Products like the Razer Pro Gaming Headset, which generated only ~$884 from 7 total orders, should be evaluated for continued viability, bundling opportunities, or potential phase-out.
- **Capitalize on successful product launches.** The PlayStation 5 Bundle and other top products significantly drove revenue spikes. Future launches should replicate successful timing, promotion, and channel strategy.

## Assumptions and Caveats

Throughout the analysis, the following assumptions and caveats were noted:

- **Data cleaning removed all null values and duplicates.** This assumes the remaining data accurately reflects the company’s transactions.
- **The dataset spans the full operational period from 2019 to early 2021.** No missing months or significant gaps are assumed.
- **Product descriptions are consistent.** Variations in naming (due to typos) were not addressed beyond trimming whitespace.
