# 🍔 Cairo Food Delivery Data Analysis (EDA)

An end-to-end **Data Cleaning and Exploratory Data Analysis (EDA)** project analyzing food delivery orders across Cairo, Egypt, throughout 2025 using Python and its data analysis ecosystem.

The project aims to uncover meaningful patterns in customer behavior, revenue performance, restaurant categories, payment preferences, and customer satisfaction to generate actionable business insights and support data-driven decision-making.

---

## 📂 Repository Structure

```text
Cairo-Food-Delivery-Data-Analysis/
│
├── Food_Delivery_Visual_Analysis.ipynb
├── food_delivery_orders.csv
└── README.md
```

- **Food_Delivery_Visual_Analysis.ipynb:** Contains the complete data cleaning, preprocessing, exploratory analysis, and visualization workflow.
- **food_delivery_orders.csv:** Dataset containing food delivery order records across Cairo.
- **README.md:** Project documentation, methodology, and key findings.

---

## 🛠️ Technologies & Libraries

| Tool | Purpose |
|---|---|
| Python | Programming and data analysis |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Static data visualization |
| Seaborn | Statistical data visualization |
| Plotly | Interactive visualizations |
| Jupyter Notebook | Data analysis environment |

---

## 🧹 Data Cleaning & Preprocessing

The dataset underwent several preprocessing steps to improve data quality and ensure reliable analysis:

1. **Missing Values Handling:** Identified and handled missing values across relevant columns to maintain data consistency.
2. **Data Type Conversion:** Converted date and time columns into appropriate datetime formats to enable time-based analysis.
3. **Text Standardization:** Cleaned and standardized inconsistent text values across payment methods, delivery areas, and restaurant categories.
4. **Outlier Detection:** Examined numerical features, including order amounts, item counts, and customer ratings, to identify potential anomalies.
5. **Data Preparation:** Prepared and transformed relevant features to support accurate aggregation and exploratory analysis.

---

## 📊 Key Insights & Business Findings

### 1. 📈 Monthly Revenue Performance

Monthly revenue showed a strong upward trend throughout 2025, increasing from approximately **76K in January** to over **185K in December**.

This represents an approximate **143% increase** in revenue over the year, indicating substantial growth in the recorded business activity.

### 2. 🍔 Restaurant Category Performance

- **Burgers** ranked first with over **1,000 successfully delivered orders**.
- **Pizza** and **Shawerma** followed as other leading restaurant categories.
- Delivered orders consistently represented a larger share than Cancelled and Refunded orders across the analyzed categories.

### 3. 💳 Customer Payment Preferences

Cash and Credit Card were the most frequently recorded payment methods, with nearly identical shares.

| Payment Method | Percentage |
|---|---:|
| Cash | 31.1% |
| Credit Card | 30.9% |
| Wallet | 18.7% |
| InstaPay | 11.9% |
| Cash On Delivery | 7.42% |

Digital payment methods, including Wallet and InstaPay, accounted for approximately **30.6%** of recorded orders, highlighting the adoption of alternative payment options.

### 4. 📅 Weekly Ordering Patterns

Average order values remained relatively stable throughout the week, ranging between **260 and 277**.

- **Sunday:** Highest average order value (277).
- **Thursday:** Second-highest average order value (274).

These findings suggest relatively consistent customer spending patterns across different days of the week.

### 5. 📍 Customer Ratings Across Areas & Platforms

Customer ratings were explored across several Cairo districts, including:

- Zamalek
- Dokki
- Heliopolis
- Nasr City
- New Cairo
- Maadi
- Sheikh Zayed
- 6th of October

The analysis also examined rating patterns across different platforms: **Android, iOS, and Web**, providing a comparative view of customer satisfaction across locations and devices.

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Ammar-Mostafa-f/Cairo-Food-Delivery-Data-Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Cairo-Food-Delivery-Data-Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas matplotlib seaborn plotly jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Food_Delivery_Visual_Analysis.ipynb` and run the cells.

---

## 🎯 Project Objectives

Through this project, I applied practical data analysis techniques to transform raw order records into meaningful insights, focusing on:

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Time-based and categorical analysis.
- Statistical exploration.
- Data visualization and business insight generation.

**This project demonstrates my practical application of Python and Pandas in analyzing real-world-style business scenarios and extracting insights that can support data-driven decisions.**
