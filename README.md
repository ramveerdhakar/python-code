# E‑commerce Furniture Dataset 2024

This dataset contains 2,000 furniture product records scraped from AliExpress, including product details, pricing, and sales metrics for online furniture items in 2024.[1]

### Dataset Description

- **Domain**: E‑commerce / Furniture retail
- **Rows**: 2,000 products
- **Columns**:  
  - `productTitle`: Name/description of the furniture item.
  - `originalPrice`: Original listed price before discount (may be missing for many rows).
  - `price`: Current selling price.
  - `sold`: Number of units sold.
  - `tagText`: Text tags such as “Free shipping” or other shipping/offer information.

The data is suitable for exploratory data analysis, pricing analysis, and machine learning tasks like sales prediction and discount impact modeling.
***

## Problem Statement

Online furniture retailers must decide how to price products and design promotions to maximize sales while remaining competitive in a crowded marketplace.  This dataset provides historical information on product titles, prices, discounts (via `originalPrice` vs `price`), shipping tags, and observed units sold for AliExpress furniture listings.

Using this data, the core problem is to understand how product attributes, price levels, and promotional signals (e.g., free shipping) relate to sales volume, and to build models that can predict the expected number of units sold for new or existing products under different pricing and promotion strategies.

***

## Project Tasks

In this project, the goal is to perform end‑to‑end data analysis and modeling on the e‑commerce furniture dataset to extract business insights and build a predictive model for product sales.  I have done:

- Clean and preprocess the data (handle missing `originalPrice`, standardize `price`, encode `tagText`, and process `productTitle`).
- Conduct exploratory data analysis to understand distributions of `price` and `sold`, and visualize relationships between price, discount, tags, and sales.
- Engineer meaningful features such as discount percentage and text‑based features from `productTitle` (e.g., TF‑IDF).
- Train and evaluate regression models (for example, Linear Regression and Random Forest Regressor) to predict `sold` based on product attributes and pricing.
- Interpret model results to provide actionable recommendations on pricing and promotion strategies for furniture sellers on e‑commerce platforms.












