# 🚀 E-Commerce Analytics & Customer Intelligence System

This project implements a **production-grade Analytics System** to analyze customer behavior, product performance, churn risk, and retention trends using structured data pipelines and business-focused analytics.

The system transforms raw transaction logs into **business-ready insights** through:
- Feature engineering  
- KPI frameworks  
- RFM customer segmentation  
- Churn classification  
- Cohort retention analysis  

---

## 🧠 Problem Statement

Understanding customers, revenue drivers, and churn risk is critical in data-driven organizations.

This project answers business-critical questions:
- Who are my **highest-value customers**?
- Which customers are at **churn risk**?
- Which products and regions generate the most revenue?
- How strong is **customer retention** over time?
- Which segments drive profitability?

---

### 🔹 Dataset Columns

| Column | Description |
|--------|-------------|
| InvoiceNo | Unique invoice identifier |
| StockCode | Product ID |
| ProductName | Item name |
| Quantity | Units purchased |
| InvoiceDate | Transaction timestamp |
| Price | Unit price |
| CustomerID | Unique customer ID |
| Country | Customer country |
| TotalAmount | Revenue per transaction |

---

### 🎯 Key Outputs (Targets)

- Revenue contribution  
- Customer value score  
- Churn risk label  
- Retention rate  
- Business KPIs  

---

## ⚙️ Tech Stack

| Layer | Technologies |
|--------|-------------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Analytics | RFM, Cohort Analysis |
| Modeling | Logistic Regression, RandomForest |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter |
| Version Control | Git, GitHub |
| Storage | CSV pipeline |
| Automation | Modular `.py` utilities |

---

## 🔄 Analytics Workflow

### ✅ Data Ingestion & Cleaning
- Type fixing  
- Duplicate checks  
- Missing data handling  
- Cleaned dataset saved to `data/processed`

---

### ✅ Feature Engineering
Generated:
- Revenue metrics  
- Order frequency  
- Customer lifetime aggregates  
- Time-based features  

---

### ✅ KPI Framework

Business KPIs:
- Monthly revenue  
- Average order value (AOV)  
- Revenue by country  
- Top products  
- Contribution by customer group  

---

### ✅ Customer Segmentation (RFM)

Customers scored on:

| Metric | Meaning |
|--------|--------|
| Recency | How recently they purchased |
| Frequency | How often they purchased |
| Monetary | How much they spent |

Segments:

| Segment | Meaning |
|---------|---------|
| VIP | Top-value customers |
| Loyal | Frequent buyers |
| Regular | Medium engagement |
| At Risk | High churn risk |
| Low Value | Low activity |

---

### ✅ Churn Modeling

Supervised classification predicts churn using:

- Recency  
- Frequency  
- Monetary  

Models evaluated:

- Logistic Regression  
- Random Forest  

Metrics:
- Accuracy  
- Precision / Recall  
- Confusion matrix  

---

### ✅ Cohort Analysis

Tracks customer retention by month:

- Retention matrix  
- Churn windows  
- Lifecycle visualization  


---

## 📊 Business Impact

This system helps companies:

✅ Identify high-value customers  
✅ Prevent customer churn  
✅ Improve retention strategy  
✅ Optimize product performance  
✅ Enable KPI-driven decisions  
✅ Track customer lifecycle  

---

## 🏆 Key Highlights

✅ Modular pipeline design  
✅ Business-driven KPIs  
✅ Customer intelligence analytics  
✅ Production-style data flow  
✅ Segmentation + churn modeling  
✅ Real-world structure  
✅ FAANG-ready presentation  

---

## 🚀 Future Improvements

- CLV prediction  
- Marketing attribution models  
- A/B testing  
- Dashboard deployment  
- SQL layer integration  
- Recommender systems  

---

## 👨‍💻 Author

**Girish K S**  

Data Scientists