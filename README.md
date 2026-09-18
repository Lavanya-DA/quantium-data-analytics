# Quantium Data Analytics — Retail Analytics

An end-to-end retail analytics project completed through the **Quantium Data Analytics Job Simulation**, focused on customer purchasing behaviour and store trial performance in the chips category.

## 📌 Project Overview

This project analyzes retail transaction and customer data to identify customer segments, purchasing patterns, and the impact of a store trial conducted across stores **77, 86, and 88**.

The analysis combines **Python, Pandas, statistical analysis, and Power BI** to transform raw retail data into actionable business insights.

## 🎯 Business Objectives

- Understand customer purchasing behaviour
- Identify high-value and high-volume customer segments
- Analyse average customer spending
- Evaluate the performance of trial stores against matched control stores
- Measure sales uplift during the trial period
- Determine whether growth was driven by customer acquisition or increased spending
- Develop data-driven recommendations for future retail strategy

## 🔄 Project Workflow

### 1. Data Preparation

- Loaded transaction and customer datasets using Python
- Inspected data structure, data types, and quality
- Converted transaction dates into datetime format
- Reviewed product information and filtered the chips category
- Identified and removed abnormal transaction quantities
- Extracted product pack sizes and brand names
- Standardised brand names
- Merged transaction and customer datasets

### 2. Customer Analytics

Analysed customers based on:

- Lifestage
- Premium customer segment
- Total sales
- Customer count
- Average spend per customer
- Average pack size

### 3. Store Trial Analysis

Evaluated three trial stores:

- Store 77
- Store 86
- Store 88

Each trial store was compared against a matched control store to estimate sales uplift during the trial period.

### 4. Statistical Analysis

Performed:

- Control-store matching
- Correlation analysis
- Sales uplift calculations
- Customer-count comparisons
- Transactions-per-customer analysis
- Statistical significance testing using a 95% confidence level

### 5. Business Recommendations

Converted analytical findings into recommendations focused on:

- Store trial expansion
- Customer acquisition
- Increasing basket size
- Young Singles/Couples
- Family customer retention

## 📊 Key Findings

### Customer Segments

Older Families and Young Families recorded the highest average spend per customer, at approximately **$32–$35**.

Young Singles/Couples represented the largest customer group, with **7,917 Mainstream shoppers**, but had a comparatively low average spend per customer of **$18.64**.

### Store Trial

The trial analysis showed substantial sales uplift across the three trial stores.

| Trial Store | Feb 2019 | Mar 2019 | Apr 2019 |
|---|---:|---:|---:|
| Store 77 | -5.9% | +36.7% | **+62.3%** |
| Store 86 | +5.6% | **+31.6%** | +3.5% |
| Store 88 | +16.3% | +20.9% | **+39.6%** |

### Main Driver of Growth

The analysis indicated that sales growth was driven mainly by **increased customer numbers rather than larger baskets**.

| Trial Store | Customer Uplift | Transactions per Customer |
|---|---:|---:|
| Store 77 | +26.8% | -2.0% |
| Store 86 | +13.7% | +0.7% |
| Store 88 | +14.3% | +8.3% |

Store 88's matched control had a weaker pre-trial correlation than the other control stores, so its result requires additional caution when interpreting the trial effect.

## 💡 Business Insights

### 1. Families represent high customer value
Older and Young Families recorded the highest average spending per customer.

### 2. Young Singles/Couples represent a basket-growth opportunity
Although this group had the largest customer base, their average spend per customer was relatively low.

### 3. Customer acquisition was the main trial driver
The strongest changes during the trial were associated with increases in customer numbers.

### 4. Store 77 recorded the highest monthly uplift
Store 77 reached a **62.3% sales uplift in April 2019** compared with its matched control.

### 5. Control-store quality matters
Store 88 had a weaker control match, highlighting the importance of selecting comparable stores when evaluating trials.

## 📈 Recommendations

### Expand the Tested Initiative
Extend the tested store initiative to a wider set of stores while continuing to monitor performance.

### Grow Basket Size Among Young Singles/Couples
Potential strategies include:

- Multi-buy offers
- Larger-pack promotions
- Targeted product combinations
- Basket-building promotions

### Retain High-Value Family Customers
Potential strategies include:

- Loyalty offers
- Family-oriented promotions
- Repeat-purchase incentives
- Larger-pack offers

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Power BI**
- **Jupyter Notebook**
- **Statistical Analysis**

## 📁 Repository Structure

```text
quantium-data-analytics/
│
├── tasks/
│   ├── Task1.pdf
│   ├── Task2.pdf
│   └── Task3 (Report).pdf
│
├── notebooks/
│   ├── Task1.ipynb
│   └── Task2.ipynb
│
├── outputs/
│   └── Project visualizations
│
├── report/
│   └──Mailreport.pdf
│   └── Report.pdf
│
└── README.md
