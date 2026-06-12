# Bike Buyer Demographics and Conversion Analysis

## 📌 Project Overview
This personal project focuses on analyzing customer demographics and purchasing behavior to understand the key factors that drive bike purchase conversions. Using a dataset containing customer profiles (income, age, education, commute distance, etc.), the goal is to uncover insights into which customer segments are most likely to convert (`Purchased Bike = Yes`) to help businesses optimize their targeted marketing strategies.

---

## 🛠️ Data Cleaning & Transformation (Data Quality Management)
Before building the dashboard, a rigorous data cleaning process was executed to ensure data integrity and accuracy:
1. **Duplicate Removal:** Identified and removed duplicate records to prevent skewed analysis.
2. **Data Standardization & Formatting:** * **Marital Status Column:** Standardized abbreviated values (e.g., `M` and `S`) into clear, full-text values (`Married` and `Single`).
   * **Gender Column:** Standardized `M` and `F` values into proper categorical descriptors (`Male` and `Female`).
3. **Feature Engineering (Age Bracket):** Created a conditional custom column to group customer ages into business-friendly demographics:
   * `Adolescent` : Age strictly below 25
   * `Middle Age` : Age between 25 and 54
   * `Old` : Age 55 and above

---

## 📊 Interactive Dashboard Features
The final interactive dashboard was built using **Microsoft Excel**, applying clean design principles and dynamic filtering:
* **Key Visualizations:**
  * **Average Income Per Purchase:** A clustered column chart displaying the purchasing power of Male vs. Female buyers against non-buyers.
  * **Customer Age Bracket:** A trend analysis showing bike purchase conversions across different generational stages.
  * **Customer Commute:** An exploration of how daily travel distance impacts the likelihood of buying a bicycle.
* **Dynamic Slicers (Interactive Filters):** Users can filter the entire dashboard seamlessly by **Marital Status**, **Region** (Europe, North America, Pacific), and **Education Level** to uncover deep-dive micro-insights.

---

## 💡 Key Preliminary Insights
* **Income Influence:** Customers with higher average incomes (particularly males around the 120,000 threshold and females around 70,000) show a stronger conversion rate for bike purchases.
* **Commute Correlation:** Daily travel distance plays a critical role; analyzing the commute curve reveals specific distance thresholds where bicycle adoption drops or spikes.

---

## 🚀 Technical Skills Demonstrated
* Data Cleaning & Validation (Handling inconsistent categorical inputs)
* Feature Engineering (Conditional logic and segmentation)
* Data Aggregation (Pivot Tables & Summarization)
* Data Visualization & Dashboard Design (Excel Charts, Slicers, UI/UX formatting)
