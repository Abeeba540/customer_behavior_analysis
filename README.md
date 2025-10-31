# customer_behavior_analysis
 Data Analytics Project showcasing customer behavior analysis using  Python, SQL and Power BI.

# 🛍️ **Customer Shopping Behavior Analysis**

## 📘 **Overview**
This project provides an **end-to-end data analytics solution** exploring how customers shop, what influences their purchases, and how businesses can improve **sales, marketing, and customer loyalty**.  

It showcases practical skills in:
- **Python** for data cleaning and EDA  
- **SQL (PostgreSQL)** for business queries  
- **Power BI** for visualization  
- **Gamma & PowerPoint** for insights presentation  

> 💡 **Business Question:**  
> How can the company leverage customer shopping data to identify trends, improve engagement, and optimize marketing strategies?

---

## 📂 **Dataset**
- **Name:** Customer Shopping Behavior Dataset  
- **Source:** Simulated retail transactions  
- **Records:** 3,900  **Columns:** 18  
- **Key Attributes:**
  - **Demographics:** Age, Gender, Location, Subscription Status  
  - **Purchases:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
  - **Behavior:** Discount Applied, Promo Code Used, Review Rating, Shipping Type  
- **Missing Values:** 37 in *Review Rating* (imputed by category median)  

---

## 🧰 **Tools & Technologies**

| Category | Tools Used |
|-----------|-------------|
| **Programming** | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| **Database** | PostgreSQL + SQLAlchemy |
| **Visualization** | Power BI |
| **Reporting** | Gamma App, PowerPoint |
| **Environment** | Jupyter Notebook / VS Code |

---

## 🧮 **Workflow & Methodology**

### 1️⃣ **Data Preparation & EDA (Python)**
📄 File: `Customer_Shopping_Behavior_Analysis.ipynb`



- Imported and explored dataset using Pandas.  
- Imputed missing values and standardized columns.  
- Created new features:
  - `age_group` — age-based segmentation  
  - `purchase_frequency_days` — interval between purchases  
- Checked redundancy between `discount_applied` and `promo_code_used`.  
- Loaded the cleaned data into **PostgreSQL** for SQL-based analysis.  

---

### 2️⃣ **SQL Business Analysis (PostgreSQL)**
📄 File: `customer_behavior_sql_queries.sql`

Key analytical queries:
| # | Objective | Business Insight |
|---|------------|------------------|
| 1 | Revenue by Gender | Female customers generate slightly higher revenue. |
| 2 | Discount vs Spending | Some customers spend above average even with discounts. |
| 3 | Top 5 Products by Rating | Dresses and blouses have the highest satisfaction. |
| 4 | Shipping Type Impact | Express users spend 12% more on average. |
| 5 | Subscription Impact | Subscribers spend 68% more and drive 45% of total revenue. |
| 6 | Discount-Dependent Products | Identified top 5 most discount-driven items. |
| 7 | Customer Segmentation | 50% new, 35% returning, 15% loyal customers. |
| 8 | Top 3 Products per Category | Highlighted bestsellers in each category. |
| 9 | Repeat Buyers & Subscription | Frequent buyers are 2× more likely to subscribe. |
| 10 | Revenue by Age Group | 25–40 age group contributes the most revenue. |

---

### 3️⃣ **Dashboard (Power BI)**
📊 File: `customer_behavior_dashboard.pbix`

<img width="900" height="490" alt="customer_behavior_dashboard" src="https://github.com/user-attachments/assets/e3ecc947-e19b-4944-b77f-aeba234c00dd" />


#### **Key Dashboard Pages**
1. **Sales Overview:** Total Revenue, Avg. Purchase, Orders, Discounts  
2. **Customer Insights:** Age, Gender, Subscription Analysis  
3. **Product & Shipping Trends:** Top-rated products, shipping comparison  
4. **Customer Segmentation:** New vs Returning vs Loyal breakdown  

> Dashboard is connected to PostgreSQL for **live data updates**.

---

### 4️⃣ **Report & Presentation**
📄 **Files:**  
- `Customer Shopping Behavior Analysis.pdf`  
- `Customer-Shopping-Behavior-Analysis.pptx`  

The report and presentation summarize:
- EDA findings  
- SQL-based insights  
- Power BI visualizations  
- Business recommendations  

> 🎯 Both were designed for **business stakeholders**, blending storytelling with data-driven insights.

---

## 💡 **Key Findings**
- 👩‍💼 Female customers generate **slightly higher total revenue** than males.  
- 💰 **Subscribers** spend **68% more** and make **45% of total purchases**.  
- 🚀 **Express shipping** users spend **12% more** than standard users.  
- ⭐ **Blouses** and **Dresses** rank top for customer satisfaction.  
- 🔁 **Loyalty rate:** 78% of subscribers are repeat buyers.  

---

## 🧠 **Recommendations**
✅ **Boost Subscriptions:** Offer exclusive deals and personalized perks.  
✅ **Launch Loyalty Programs:** Reward repeat buyers to encourage retention.  
✅ **Refine Discount Strategy:** Maintain discounts for strategic categories only.  
✅ **Targeted Marketing:** Focus on 25–40 age group and express shipping users.  
✅ **Promote High-Rated Products:** Feature top-rated items in ads and campaigns.  

---

## ⚙️ **How to Run the Project**

1. **Clone this Repository**
   ```bash
   git clone https://github.com/Abeeba540/customer_behavior_analysis.git
   cd customer_behavior_analysis
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run EDA**
   - Open and execute `Customer_Shopping_Behavior_Analysis.ipynb`.

4. **Set Up Database**
   - Create a PostgreSQL database `customer_behavior`.  
   - Update connection details in the Python script.  
   - Run all SQL queries from `customer_behavior_sql_queries.sql`.

5. **Power BI Dashboard**
   - Open `customer_behavior_dashboard.pbix`.  
   - Connect to your PostgreSQL instance.

6. **View Final Outputs**
   - 📄 `Customer Shopping Behavior Analysis.pdf`  
   - 📊 `customer_behavior_dashboard.pbix`  
   - 🎥 `Customer-Shopping-Behavior-Analysis.pptx`

---

## 📦 **Deliverables**
- 🐍 `Customer_Shopping_Behavior_Analysis.ipynb` – Python EDA & cleaning  
- 🗃️ `customer_behavior_sql_queries.sql` – SQL queries for analysis  
- 📊 `customer_behavior_dashboard.pbix` – Power BI interactive dashboard  
- 📄 `Customer Shopping Behavior Analysis.pdf` – Final analytical report  
- 🖼️ `Customer-Shopping-Behavior-Analysis.pptx` – Executive presentation  

---

## 👩‍💻 **Author**
**Ummu Abeeba**  
📧 [abeeba2430@gmail.com](mailto:abeeba2430@gmail.com)  
🌐 [GitHub: Abeeba540](https://github.com/Abeeba540)  
💼 *Aspiring Data Analyst | Skilled in Python, SQL, Power BI & Data Storytelling*
