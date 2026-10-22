# clothing-brand-sales-dashboard
clothing-brand-sales-dashboard
# Clothing Brand Sales: Customer Behaviour Dashboard

An interactive Power BI dashboard that explores customer behaviour for a clothing brand: who the customers are, what they buy, and how subscription status and shipping preferences relate to spending.


## Overview

The dashboard is a single-page report that summarises key customer metrics and lets you slice the data by subscription status, gender, product category and shipping type.

## Key metrics (KPI cards)

| Metric | Description |
|---|---|
| **Number of Customers** | Total customers in the current filter selection |
| **Average Purchase Amount** | Mean purchase value per customer |
| **Average Review Rating** | Mean customer review rating |

## Visuals

- **Subscription status (donut chart):** share of customers who are subscribed vs. not subscribed.
- **Purchase amount by category (column chart):** total revenue per product category.
- **Customers by category (column chart):** number of customers per product category.

## Filters (slicers)

- Subscription status
- Gender
- Category
- Shipping type

All visuals and KPI cards update together when a filter is applied.

## Data

- **Table:** `clothing_brand_db customers`
- **Fields used:** `customer_id`, `gender`, `category`, `purchase_amount`, `subscription_status`, `shipping_type`, review rating

> Add the source of your dataset here (e.g. Kaggle link) and note any cleaning steps.

## Tools

- Power BI Desktop
- DAX measures for the KPI cards
- Custom background and layout (1920 × 1080)

## How to open

1. Download `Clothing_Brand_Sales.pbix` from this repository.
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. Use the slicers on the right to explore the data.

## Repository structure

```
├── dashboard/
│   └── Clothing_Brand_Sales.pbix
├── images/
│   └── dashboard.png
└── README.md
```

## Key insights

> Fill this in after exploring the dashboard, for example:
> - Which category brings in the most revenue?
> - Do subscribers spend more than non-subscribers?
> - Does shipping type relate to purchase amount or ratings?

## Author

Ajay Sabbani
