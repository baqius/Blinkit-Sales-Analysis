# Blinkit Sales Analysis Dashboard

An interactive **Power BI** dashboard analysing sales performance for **Blinkit (India's Last Minute App)** across outlets, locations, item categories and fat content. The dashboard turns 8,523 item-level records into a single view that helps stakeholders see what sells, where it sells, and which outlet formats drive revenue.

---

## Project Overview

Blinkit operates a network of outlets of different sizes, types and city tiers. This project analyses sales data to understand how product attributes (item type, fat content) and outlet attributes (type, size, location, establishment year) influence revenue and customer ratings.

## Business Objectives

- Measure overall sales performance and customer satisfaction.
- Identify top-performing item categories.
- Compare sales across outlet types, sizes and city tiers.
- Understand the impact of fat content on sales.
- Analyse how outlet age (establishment year) relates to revenue.

## Key Performance Indicators

| KPI | Value |
|---|---|
| Total Sales | $1.20M |
| Average Sales per Item | $140.99 |
| Number of Items | 8,523 |
| Average Rating | 4 |

## Dashboard Features

- **KPI cards** for Total Sales, Average Sales, Number of Items and Average Rating.
- **Metric toggle** to switch the main charts between Total Sales, Avg Sales, No of Item and Avg Rating.
- **Fat Content** donut chart (Low Fat vs Regular) and a **Fat by Outlet** breakdown by tier.
- **Item Type** bar chart ranking 16 product categories.
- **Outlet Establishment Year** trend line.
- **Outlet Size** donut chart (Medium, Small, High).
- **Outlet Location** funnel by tier (Tier 1, 2, 3).
- **Outlet Type** summary table with Total Sales, Avg Sales, No of Items, Avg Rating and Item Visibility.
- **Slicers** for Outlet Location, Outlet Size and Item Type.

## Key Insights

**Fat content**
- Low Fat items generate **$776.32K (about 65%)** of sales versus **$425.36K (about 35%)** for Regular.
- Low Fat leads in every tier, e.g. Tier 3: $0.31M vs $0.17M.

**Item type**
- **Fruits & Vegetables** and **Snack Foods** are the top categories at about **$0.18M each**, followed by Household ($0.14M) and Frozen Foods ($0.12M).
- Seafood, Breakfast, Starchy Foods and Others are the smallest, at $0.02M or less.

**Outlet location**
- **Tier 3** cities lead with **$472.13K**, followed by Tier 2 ($393.15K) and Tier 1 ($336.40K). Tier 1 sales are about 71.3% of Tier 3.

**Outlet size**
- **Medium** outlets lead ($507.90K), then Small ($444.79K) and High ($248.99K).

**Outlet type**
- **Supermarket Type1** dominates with **$787.5K (about 66% of sales)** and 5,577 items.
- Grocery Store ($151.9K), Supermarket Type2 ($131.5K) and Supermarket Type3 ($130.7K) trail well behind.
- Average sales per item is nearly identical across outlet types (about $140 to $142), so revenue differences come mainly from **volume**, not price per item.
- Average rating is 4 across all outlet types.

**Outlet establishment year**
- Outlets established around the late 1990s show the highest sales (**$205K**).
- Sales are otherwise flat at about **$130K** per establishment year, apart from a sharp dip to **$78K** around 2011.

## Recommendations

1. **Expand Low Fat and top-category assortments** (Fruits & Vegetables, Snack Foods), which already drive the most revenue.
2. **Prioritise Tier 3 and Tier 2 growth**, as they outperform Tier 1 in sales.
3. **Invest in Supermarket Type1 outlets**, the main revenue engine, while reviewing the potential of Type2 and Type3.
4. **Investigate the 2011 establishment-year dip** to see whether it reflects fewer outlets, product mix or data issues.
5. **Grow volume rather than price**, since average sales per item is uniform across formats.

## Tech Stack

- **Power BI Desktop** (data modelling, DAX measures, visuals, slicers)
- Source data: Blinkit item and outlet sales dataset *(add source / link here)*
