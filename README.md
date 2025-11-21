# 🛍 Retail Store Data Analysis

## 📌 Project Overview
This project analyzes retail store transaction data to uncover **sales trends**, **customer behavior**, and **segmentation insights**. The workflow includes:
- ✅ Data Cleaning
- ✅ Exploratory Data Analysis (EDA)
- ✅ Trend Analysis
- ✅ Customer Segmentation (RFM-based)

---

## 📂 Dataset Structure
- **Rows:** 12,575 transactions
- **Columns:** transaction_id, customer_id, category, item, price_per_unit, quantity, total_spent, payment_method, location, transaction_date, discount_applied, year, month

---

## 🔍 Workflow
1. **Data Cleaning:** Removed duplicates, handled missing values, converted data types.
2. **EDA:** Summary statistics, correlation analysis.
3. **Trend Analysis:** Yearly, monthly, and seasonal sales patterns.
4. **Customer Segmentation:** Identified VIP and regular customers.
5. **Insights & Recommendations:** Actionable strategies for business growth.

---

## 📊 Visual Insights & Analysis

### **A. Sales Performance Analysis**
#### 1. Yearly Sales Comparison
<img width="895" height="583" alt="2) Yearly Sales Comparison" src="https://github.com/user-attachments/assets/3aaea822-062a-412a-8e10-0a0f01b08665" />

- **Observation:** Sales peaked in 2024 (~554K), followed by 2022(~539K) and 2023(~515K). 2025 shows a sharp decline (Incomplete data as only January 2025 is available).
- **Action:** Investigate reasons for 2023 drop; replicate successful strategies from 2024.

#### 2. Monthly Sales Trend with Moving Average
<img width="1077" height="573" alt="1) Monthly Sales Trend with Moving Average" src="https://github.com/user-attachments/assets/a78ea413-c75a-4e05-b428-732897d0c187" />

- **Observation:** Sales fluctuate between 40K–55K monthly; peaks in December to February.
- **Action:** Plan seasonal campaigns and stock for Q4 and Q1

#### 3. Month-over-Month Growth Rate
<img width="1057" height="580" alt="3) Month-over-Month Growth Rate" src="https://github.com/user-attachments/assets/399d019f-63a4-4461-b8db-36d1c7b7210a" />

- **Observation:** Growth is volatile; but a clear trend of sales upsurge in the Q4 end to early Q1
- **Action:** Investigate operational or market factors causing high growth in Q4 end to early Q1 and try to replicate for other periods.

#### 4. Average Monthly Sales Trend
<img width="1056" height="640" alt="4) Seasonal Sales Patterns" src="https://github.com/user-attachments/assets/49b4d74e-bc8c-4c5b-bf97-811c0c7bcc22" />

- **Observation:** January shows highest average sales; August lowest.
- **Action:** Seasonal campaigns should target Q1 for maximum impact.

#### 5. Average Monthly Sales by Year
<img width="1352" height="640" alt="8) Average Monthly Sales by Year" src="https://github.com/user-attachments/assets/929426a4-65bb-45ba-9dad-0eb6c059d878" />

- **Observation:** 2024 consistently outperforms other years across months.
- **Action:** Replicate successful strategies from 2024.

---

### **B. Product & Category Analysis**
#### 7. Category-wise Sales Distribution
<img width="832" height="568" alt="1) Category wise Sales Distribution" src="https://github.com/user-attachments/assets/1350d31a-4640-4b18-bb56-1ab9d69fd626" />

- **Observation:** Butchers (217K) and Electric Essentials (213K) lead; Milk Products lowest (190K).
- **Action:** Focus on top-performing categories for promotions.

#### 8. Top 10 Items by Total Sales
<img width="657" height="286" alt="2) Top 10 Items by Total sales" src="https://github.com/user-attachments/assets/45323c0e-3158-45a9-af9d-173d2a825733" />

- **Observation:** Furniture and Electric Household Essentials dominate top-selling items.
- **Action:** Focus marketing and inventory on these high-value categories.

#### 9. Top 10 Items by Average Price per Unit
<img width="593" height="302" alt="4) Top 10 Items with highest Average price per unit" src="https://github.com/user-attachments/assets/5e848f70-3882-4984-a39e-4c2a5aa1e4ec" />

- **Observation:** Most of the high priced items are priced around \$41; slight variation in Food and Electric Essentials.
- **Action:** Explore premium pricing for high-demand items.

---


## **C. Customer Analysis**
#### 10. Most Frequent Customers (Regular Buyers)
<img width="645" height="307" alt="2  Top 10 customers by highest total sales with top category (VIP customers)" src="https://github.com/user-attachments/assets/875cf393-b0fb-4e2e-82b2-83cae752e710" />

- **Observation:** CUST_24 spent the most (~71K), followed by CUST_08 and CUST_05.
- **Action:** Launch loyalty programs for these regular buyers.

#### 11. Top 10 Customers by Total Sales (VIP Customers)
<img width="645" height="307" alt="2  Top 10 customers by highest total sales with top category (VIP customers)" src="https://github.com/user-attachments/assets/482fb3b1-3237-48cd-b250-5cb37529b78c" />

- **Observation:** CUST_24 spent the most (~71K), followed by CUST_08 and CUST_05.
- **Action:** Need to Focus on these Customers since they are both Frequent customers and top buyers:** CUST_24, CUST_08, CUST_05, CUST_13, CUST_23


---

### **D. Payment & Discount Analysis**
#### 13. Payment Method Distribution
<img width="400" height="340" alt="5) Payment Method Distribution" src="https://github.com/user-attachments/assets/e9f7bc99-5bcb-435f-abb2-ca2543a16335" />

- **Observation:** Cash (34.3%), Digital Wallet (33%), Credit Card (32.8%) – balanced usage.
- **Action:** Promote wallet-based discounts to encourage digital adoption.

#### 14. Discount Impact Analysis
<img width="702" height="431" alt="9) Discount Impact Analysis" src="https://github.com/user-attachments/assets/a637b782-1d62-4ae5-b020-4a05445fb385" />

- **Observation:** Discounts slightly reduce average spending per transaction.
- **Action:** Optimize discount strategy to boost volume without eroding margins.

---

### **E. Correlation Analysis**
#### 15. Correlation Matrix
<img width="606" height="467" alt="6) Correlation Analysis" src="https://github.com/user-attachments/assets/9f299b26-5e06-4b67-98f5-6155e41bd350" />

- **Observation:** Quantity and Total Spent have strong correlation (0.71).
- **Action:** Upsell strategies to increase quantity per transaction.

---

## ✅ Key Recommendations
- Implement **loyalty programs** for frequent buyers.
- Launch **seasonal campaigns** from December to February
- Promote **digital wallet offers** to leverage adoption trend.
- Optimize **discount strategy** for profitability.
- Replicate **successful 2024 strategies** for future growth.

---

## 🛠 Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/retail-store-analysis.git
