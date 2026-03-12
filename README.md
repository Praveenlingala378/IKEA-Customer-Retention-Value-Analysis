<img width="731" height="538" alt="image" src="https://github.com/user-attachments/assets/4ef3ee4a-c33d-43d4-8532-72210715b087" />
# <p align="center">🛋️ IKEA Customer Retention & Value Analysis</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Data%20Modeling-yellow?style=for-the-badge&logo=powerbi">
  <img src="https://img.shields.io/badge/DAX-Advanced%20Analytics-blue?style=for-the-badge&logo=analytics">
  <img src="https://img.shields.io/badge/SQL-Data%20Cleaning-orange?style=for-the-badge&logo=mysql">
</p>

---

## 🎯 Executive Overview
[cite_start]This project dissects IKEA’s customer lifecycle to optimize retention and loyalty program ROI. [cite_start]By engineering a robust data model and calculating **Customer Lifetime Value (CLV)**, I provided a data-driven roadmap for personalized reactivation and loyalty program optimization[cite: 117, 118].

### 📊 Key Performance Indicators (KPIs)
| Metric | Value |
| :--- | :--- |
| **Total Customers** | [cite_start]97  |
| **Churn Rate (%)** | [cite_start]51.55%  |
| **Repeat Rate (%)** | [cite_start]76.29%  |
| **Repeat Customers** | [cite_start]74  |

---

## 🛠️ The Technical Toolkit

### 🏗️ Data Architecture & ETL
* [cite_start]**Custom Tenure Logic:** Engineered a `Membership_Duration` column in Power Query to track tenure in real-time[cite: 104].
* [cite_start]**Temporal Granularity:** Extracted `Transaction_Year` and `Transaction_Month` to enable seasonal analysis[cite: 105].
* [cite_start]**Schema Design:** Established a Star Schema with 1:1 and Many-to-One relationships between Locations, Demographics, and Transactions[cite: 106].

### 🧪 Advanced DAX Engineering
I used complex DAX measures to drive business logic:
* [cite_start]**CLV Segmentation:** Used `SWITCH(TRUE())` and `PERCENTILEX.INC` to dynamically categorize customers into High, Medium, and Low segments.
* [cite_start]**Churn Metrics:** Developed a robust `DIVIDE` measure to track the churn rate and prevent calculation errors[cite: 107].
* [cite_start]**Customer Tiering:** Defined tiers based on purchase frequency (e.g., High-Tier: >= 11 purchases)[cite: 111, 113].

---

## 💡 Strategic Insights & Recommendations
* [cite_start]**Reward Visibility:** A gap between points earned and redeemed indicates an opportunity to improve reward incentives and visibility.
* [cite_start]**High-Income Churn:** The High-Income group exhibits the highest churn rate (0.55), suggesting a need for exclusive premium benefits[cite: 107].
* [cite_start]**Localized Strategy:** Older stores and specific regions (Liverpool, Birmingham) show higher churn, requiring localized engagement initiatives.


<p align="center"><i>Professional Portfolio | Praveen Sai Lingala</i></p>
