# 🧭 Tourism Trend Analysis

## 📘 Overview
This project focuses on analyzing **travel package data** obtained from the **Travel Triangle** website.  
It examines **trip duration**, **pricing**, **discounts**, and **tour types** to identify key **patterns, trends, and relationships** in tourism data.  
The findings help **travel platforms and agencies** optimize package design, pricing strategies, and promotional offerings based on customer preferences and spending behavior.

---

## 🎯 Objective
To analyze large volumes of travel package data and uncover **meaningful trends** in:
- Package pricing and discounts  
- Trip duration and type  
- Relationships between trip cost, duration, and discounts  

The ultimate goal is to provide **data-driven insights** that support better decision-making in the **tourism industry**.

---

## 🧩 Problem Statement
Travel platforms face challenges in evaluating thousands of travel packages to identify useful trends.  
Without systematic data analysis, it’s difficult to:
- Determine competitive pricing  
- Highlight attractive offers  
- Understand customer preferences  

This project applies **data analytics and visualization** techniques to address those gaps and improve travel business intelligence.

---

## 🧮 Dataset Description
- **Source:** Travel Triangle (web scraped)  
- **Records:** 936 travel deals  
- **Attributes:**  
  - Package title  
  - Destination  
  - Trip duration  
  - Original price  
  - Discounted price  
  - Discount percentage  
  - Trip type  

---

## 🧼 Data Cleaning & Preparation
- Removed **duplicate records**  
- Converted **price values** to numeric (removed commas)  
- Standardized **trip duration** (e.g., extracted numeric values from “5 Days / 4 Nights”)  
- Handled **missing values** for consistency  
- Calculated **discount percentage** and **amount saved**

---

## 🔍 Data Analysis Performed
- **Trip Duration Distribution:** Most trips are **3–6 days**, showing customer preference for short holidays.  
- **Price Distribution:** Right-skewed — most packages are moderately priced with a few luxury outliers.  
- **Discount Analysis:** Higher discounts often appear in **premium or high-value packages**.  
- **Duration vs. Price:** Longer trips tend to be more expensive, but luxury short trips also exist.  
- **Trip Type Trends:** Discounts influence popularity, with certain trip types becoming more attractive.

---

## 🧰 Technologies Used
- **Python 3**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Jupyter Notebook**

---

## ⚙️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<bhavi1501>/tourism-trend-analysis.git
   cd tourism-trend-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "tourism_trend_analysis.ipynb"
   ```

---

## 📊 Key Insights
- **Short-duration trips** dominate the dataset.  
- **Pricing positively correlates with duration**, though luxury short trips exist.  
- **Discounts vary by destination**, influenced by seasonality and competition.  
- **Outliers** often represent luxury or custom tour packages.

---

## 🧑‍💻 Author
**Bhavya K**  
_Data Analyst | Python Developer | EDA & Visualization Enthusiast_



---

## 🏁 Conclusion
This project highlights how **exploratory data analysis (EDA)** can reveal valuable insights in the tourism industry.  
By understanding pricing, duration, and discount trends, travel agencies can tailor offerings that meet customer demand and maximize profitability.
