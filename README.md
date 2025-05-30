Hey everyone! I'm Amit, and I'm excited to share my latest portfolio project: Sales Analysis using MySQL.
grateful to Data With Baraa for the guidance and knowledge shared throughout the learning journey!

# ✅ Sales Analysis Project - Using MySQL 

This project is a comprehensive walkthrough of **sales data analysis using SQL**. It simulates a real-world data analytics pipeline with a focus on deriving **actionable business insights** and building detailed **customer and product reports**.

---

## ▶️ Way 1 – Use a Single Script

A simplified approach for quickly running the analysis end-to-end.

### 🔹 Step 1: Load Data

Use the `LOAD DATA LOCAL INFILE` command inside the `Load Complete Data` script.  
👉 Replace the placeholder with your actual CSV file path.

![image](https://github.com/user-attachments/assets/a3127376-5f1a-4968-80cf-1d2340e258c1)


---

### 🔹 Step 2: Analyze Data

Open the `Analyze Sales Measures` script and run it section by section.  
✅ Each section is well-commented to guide you through the logic.

![image](https://github.com/user-attachments/assets/7215c604-e003-4503-9dbf-56a10e174fc7)


---

### 🔹 Step 3: Final Reporting

- `report_customers.sql`: Generates the final report summarizing customer behavior.
- `report_products.sql`: Delivers a comprehensive report on product performance.

---

## ▶️ Way 2 – Use Multiple Scripts (Modular Approach)

For more control and flexibility, run the project using individual modular SQL scripts.

---

### 📁 Project File Structure

#### 🔧 1. Data Initialization
- `00_init_database.sql`: Sets up the database and loads initial data.

---

#### 🔍 2. Data Exploration
- `01_database_exploration.sql`: Basic inspection of database structure and contents.
- `02_dimensions_exploration.sql`: Analyzing categorical dimensions.
- `03_date_range_exploration.sql`: Exploring data across different time frames.
- `04_measures_exploration.sql`: Summary statistics and key measures.

---

#### 📊 3. Analytical Modules
- `05_magnitude_analysis.sql`: Total sales values and volume analysis.
- `06_ranking_analysis.sql`: Ranking products and customers by performance.
- `07_change_over_time_analysis.sql`: Analyzing trends over time.
- `08_cumulative_analysis.sql`: Running totals and cumulative KPIs.
- `09_performance_analysis.sql`: Sales performance benchmarking.
- `10_data_segmentation.sql`: Segmenting customers and products by logic.
- `11_part_to_whole_analysis.sql`: Ratio and percentage breakdowns.

---

#### 📈 4. Final Reporting
- `12_report_customers.sql`: Final customer behavior report.
- `13_report_products.sql`: Final product performance report.

---

## 🛠️ Tools Used
- **MySQL** for query development and execution
- **CSV** as the data source
- SQL best practices for readability and performance

---

## 📬 Contact

Made with 💡 and SQL.  
Feel free to connect or explore more projects:

- [LinkedIn](https://www.linkedin.com/in/amit-babani-26613522a/)
