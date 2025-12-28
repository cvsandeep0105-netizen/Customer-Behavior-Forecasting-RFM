# Customer Behavior Forecasting & RFM-Based Segmentation

This project analyzes customer purchasing behavior using transactional retail data and applies **RFM (Recency, Frequency, Monetary) analysis** to segment customers into meaningful, business-driven groups.

The project is designed as an **end-to-end, industry-ready analytics workflow** suitable for global roles and professional portfolios.

---

## Objective
- Understand customer purchasing patterns
- Segment customers using RFM analysis
- Identify high-value, loyal, and at-risk customers
- Generate actionable business insights
- Build a 10/10 portfolio-grade data analytics project

---

## Dataset
- **Source:** UCI Machine Learning Repository (Online Retail Dataset)
- **Type:** Transactional retail data
- **Key Columns Used:**
  - Invoice (standardized)
  - Customer ID
  - InvoiceDate
  - Quantity
  - Price
  - Country

> Note: Invoice identifiers were standardized during cleaning to avoid inconsistencies.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning
- Removed missing values
- Removed negative quantities
- Converted invoice date to datetime
- Standardized column names
- Created `TotalPrice = Quantity × Price`

### 2. Feature Engineering
- Transaction-level purchase value
- Customer-level aggregation
- Total quantity, total spend, last purchase date

### 3. RFM Analysis
- **Recency:** Days since last purchase
- **Frequency:** Number of unique purchases
- **Monetary:** Total spending

Each customer receives R, F, and M scores.

### 4. Customer Segmentation
- High-value / VIP customers
- Loyal customers
- Mid-value customers
- At-risk customers

### 5. Visualization
- RFM score distribution
- Customer segment distribution
- Business-focused visual insights

---

## Business Insights
- VIP customers should receive loyalty rewards
- Mid-value customers are ideal for upselling
- At-risk customers need re-engagement campaigns
- Frequency-focused customers show strong retention potential

---

## How to Install Dependencies
```bash
pip install -r requirements.txt

## How to Open & Run the Notebook

```bash
jupyter notebook notebooks/customer_behavior_forecasting.ipynb
```

Then run **all cells from top to bottom**.

---

## Repository Structure

```
Customer-Behavior-Forecasting-RFM/
│
├── README.md
├── requirements.txt
├── data/
│   └── online_retail.csv
├── notebooks/
│   └── customer_behavior_forecasting.ipynb
├── outputs/
│   ├── rfm_segments.png
│   └── summary_insights.txt
└── docs/
    └── project_report.pdf
```

---

## Outputs Generated
- RFM scores per customer  
- Customer segmentation table  
- Visualizations for RFM distribution  
- Business insight summary  

All outputs are saved inside the **outputs/** directory.

---

## Assumptions & Limitations
- Dataset represents historical transactions only  
- No customer demographic information available  
- Snapshot date is based on the latest transaction date  
- No real-time or future forecasting implemented  

---

## Author
Venkata Sandeep Kumar Reddy
Aspiring Data Scientist | AI Engineer  
Targeting global roles in top-tier technology companies  

---

## License
This project is created for **educational and portfolio purposes** only.