# 📊 Power BI Projects: E-Commerce Return Analysis & Healthcare No-Show Prediction

## 📌 Overview

This repository showcases two real-world data analytics projects that combine **Python, Excel, and Power BI** to deliver actionable insights:

1. **E-Commerce Return Rate Reduction Analysis**
2. **Healthcare Appointment No-Show Prediction**

The workflow followed in both projects:

* **Data Cleaning & Preprocessing** → Python (Pandas, NumPy) & Excel (for initial exploration and validation).
* **Exploratory Data Analysis (EDA)** → handling missing values, and outlier detection.
* **Visualization & Dashboarding** → Power BI for building dynamic and interactive dashboards.

These projects highlight how data-driven decision-making can reduce inefficiencies, optimize processes, and improve overall performance.

---

## 🛒 Project 1: E-Commerce Return Rate Reduction Analysis

### 🔧 Data Cleaning & Preparation

* **Initial Exploration** in Excel to check nulls, formatting issues, and quick pivot views.
* Removed **duplicates** and irrelevant columns not contributing to analysis.
* Standardized column names and corrected data types (e.g., dates → datetime).
* Filled missing values for **product categories** and **customer demographics**.
* Aggregated sales and return data on a **monthly basis** for trend analysis.

### 📊 Dashboard Highlights

https://github.com/viranch08/Final_Projects_ElevateLab/blob/main/E-Commerce%20Return%20Analysis.png

**Key Insights:**

* **Return Rate is 50.52%** → Half of all orders are being returned, signaling urgent intervention required.
* **Top Returned Categories**: Home (₹1.56M), Books (₹1.53M), Clothing (₹1.52M), Toys (₹1.50M), Electronics (₹1.50M).
* **Return Reasons**: Majority of returns due to **Defective products (1327)**, **Wrong item shipped (1258)**, **Customer changed mind (1255)**, and **Not as described (1212)**.
* **Payment Method Sales**: Almost equally distributed between Credit Card (24.72%), Debit Card (24.85%), PayPal (24.7%), and Gift Cards (25.72%).
* **Monthly Trends**: Peaks in returns during **July (452 orders)**, lowest in **February (373 orders)**.
* **Customer Demographics**: Balanced gender share (Male 50.09%, Female 49.91%).

**Business Implications:**

* Implement **stringent quality checks** to cut down on defective shipments.
* Refine **warehouse operations and order verification** to prevent wrong-item deliveries.
* Provide **detailed product descriptions and images** to reduce “Not as described” complaints.
* Create **customer loyalty programs** targeting high-return categories.

---

## 🏥 Project 2: Healthcare Appointment No-Show Prediction

### 🔧 Data Cleaning & Preparation

* **Excel checks** for column consistency and duplicates.
* Filled missing values in demographics (age, gender where applicable).
* Converted **date fields** into proper datetime format.
* Encoded categorical variables (e.g., gender, SMS reminder) for better handling.
* Removed unnecessary fields (IDs, administrative-only values).

### 📊 Dashboard Highlights

https://github.com/viranch08/Final_Projects_ElevateLab/blob/main/Healthcare%20Appointment%20No%20Show%20Prediction.png

**Key Insights:**

* **Total Appointments**: 111K, with **22K no-shows (20.19%)**.
* **Demographics**: Females contribute to **65.38% of no-shows**, males 34.62%.
* **Age Factor**: Highest no-show rate in **19–30 group (24.7%)**, followed by 0–18 (21.99%).
* **SMS Reminders**: Significant impact → No-shows reduced from **56.15% (No SMS)** to **43.85% (With SMS)**.
* **Day-wise Trends**: Mondays and Tuesdays show higher no-show counts.
* **Quarterly Trend**: Q2 has lowest no-show rate (**19.72%**), Q1 the highest (**32.74%**).

**Business Implications:**

* **Increase SMS reminders** to reduce no-shows further.
* Design **youth-targeted campaigns** to improve attendance among 19–30 patients.
* Address scheduling pressure on **Mondays and Tuesdays** by redistributing slots.
* Use predictive models to **flag high-risk patients** and send multiple reminders.

---

## ⚙️ Tools & Technologies Used

* **Python** → Pandas, NumPy, Matplotlib, Seaborn (data cleaning, preprocessing, and exploration).
* **Excel** → Initial exploration, quick aggregations, pivot tables.
* **Power BI** → Interactive dashboards with slicers, filters, and drill-through analysis.

---

## 🚀 How to Reproduce

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/powerbi-projects.git
   cd powerbi-projects
   ```

2. **Data Cleaning**

   * Run the Python notebook (`cleaning_script.ipynb`) for preprocessing.
   * Alternatively, check the Excel file for initial exploration and validation.

3. **Dashboard Setup**

   * Open `.pbix` files in Power BI Desktop.
   * Refresh dataset connections to point to your local CSV/Excel files.

4. **Explore Insights**

   * Use filters (e.g., shipping method, product category, gender, SMS reminders) to interact with dashboards.

---

## 📈 Final Thoughts

* **E-Commerce Project**: Helped uncover top reasons for returns and highlighted product categories needing operational improvements.
* **Healthcare Project**: Identified demographic and behavioral drivers of no-shows, validating the effectiveness of SMS reminders.

Both projects show how combining **data cleaning with Python & Excel** and **visual storytelling with Power BI** can turn raw data into actionable strategies for business and healthcare improvements.
