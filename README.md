# 📊 Amazon Electronics Product Analysis

This project analyzes the top 20 best-selling products in the **Electronics** category on [Amazon.com](https://www.amazon.com/Best-Sellers-Electronics/zgbs/electronics). It covers product characteristics, price-performance relationships, and generates business insights.

> **Note:** All analysis is based on scraped public data. No personal or proprietary information is used.

---

## 📁 Project Structure

- `data/` : Collected product information (stored as DataFrame in runtime)
- `figures/` : Saved figures (PNG format) used in the report
- `Amazon_Electronics_Report.pdf` : Final English report with charts and product recommendations
- `amazon_analysis.ipynb` : Google Colab notebook with full code and explanations (Chinese annotations)

---

## 🔍 Analysis Overview

### Step 1: Environment Setup
Install necessary libraries and configure scraping headers.

### Step 2: Data Collection
Scrape top 20 bestsellers from Amazon's Electronics category:
- Title
- Rating
- Price
- Review count
- Product URL

### Step 3: Product Information Analysis
- Price distribution
- Rating distribution
- Price vs Rating scatter plot
- Price vs Review count scatter plot

### Step 4: Feature-Performance Correlation
- Title length vs Rating
- Correlation between pricing and user behavior

### Step 5: Business Insight & Recommendation System
- Composite scoring: Rating (50%) + Review Count (30%) + Price Affordability (20%)
- Top 5 product summaries and ranking
- Recommendation cards

### Step 6: PDF Report Generation
- Using `reportlab` to generate a clean multi-page PDF report
- Includes all figures and recommendation summaries

---
