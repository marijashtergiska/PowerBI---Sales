AdventureWorks Sales Dashboard 📊

📌 Project Overview

This project is an interactive **Power BI sales dashboard** built using the AdventureWorks dataset.

The goal of the project is to analyze sales performance, revenue, customers, products, returns, and regional performance through interactive visualizations and DAX measures.

The dashboard provides a clear overview of business performance and allows users to explore the data by different years, products, customer segments, and territories.


## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **DAX** – calculated measures and business metrics
* **Power Query** – data cleaning and transformation
* **CSV** – source data
* **GitHub** – project versioning and documentation

---

## 📂 Dataset

The project uses the AdventureWorks dataset, which contains information about sales transactions, customers, products, product categories, returns, territories, and dates.

The following datasets are used:

* 📅 **Calendar**
* 👤 **Customers**
* 📦 **Products**
* 🏷️ **Product Categories**
* 🏷️ **Product Subcategories**
* 🔄 **Returns**
* 🌎 **Territories**
* 💰 **Sales**

---

## 🔗 Data Model

The Power BI model uses relationships between the main fact tables and supporting dimension tables.

The main structure includes:

* **Sales** → Products
* **Sales** → Customers
* **Sales** → Calendar
* **Sales** → Territories
* **Products** → Product Subcategories
* **Product Subcategories** → Product Categories
* **Returns** → Products

The model allows sales and business performance to be analyzed across different dimensions such as time, customers, products, categories, and territories.

---

## 📊 Dashboard

The dashboard provides an interactive overview of AdventureWorks sales performance.

### Key areas analyzed

**💰 Revenue & Sales Performance**

* Total Revenue
* Sales performance over time
* Yearly performance
* Sales trends

**📦 Product Analysis**

* Product performance
* Product categories
* Product subcategories
* Best-performing products

**👥 Customer Analysis**

* Customer activity
* Customer purchasing behavior
* Customer-based sales analysis

**🌎 Regional Analysis**

* Sales by territory
* Regional performance
* Comparison between different territories

**🔄 Returns Analysis**

* Returned products
* Return activity
* Product return performance

---

## 📈 DAX Measures

The dashboard uses DAX measures to calculate key business metrics and enable interactive analysis.

Examples include:

```DAX
Total Revenue = 
SUMX(
    Sales,
    Sales[OrderQuantity] * Sales[UnitPrice]
)
```

Additional measures are used for analyzing sales performance, returns, customers, products, and time-based trends.

---

## 🎛️ Interactivity

The dashboard includes interactive filters and slicers that allow users to explore the data dynamically.

Users can filter the dashboard by dimensions such as:

* Year
* Date
* Product
* Product Category
* Product Subcategory
* Customer
* Territory

The visuals update automatically based on the selected filters.

---

## 💡 Key Business Questions

This dashboard can be used to answer questions such as:

* How much revenue is being generated?
* How does revenue change over time?
* Which products generate the most sales?
* Which product categories perform best?
* Which territories generate the highest revenue?
* How are customers contributing to overall sales?
* Which products have the highest number of returns?
* How does business performance vary between different years?

---

## 📷 Dashboard Preview

*Add a screenshot of the Power BI dashboard here.*

Example:

```text
![AdventureWorks Dashboard](Screenshots/Dashboard.png)
```

---

## 📁 Repository Structure

```text
AdventureWorks-PowerBI/
│
├── AdventureWorks.pbix
├── README.md
│
├── Data/
│   ├── Calendar.csv
│   ├── Customers.csv
│   ├── ProductCategories.csv
│   ├── ProductSubcategories.csv
│   ├── Products.csv
│   ├── Returns.csv
│   ├── Sales.csv
│   └── Territories.csv
│
└── Screenshots/
    └── Dashboard.png
```

---

## 🎯 Project Goals

This project was created to practice and demonstrate skills in:

* Data modeling
* Data cleaning and transformation
* DAX
* Power BI dashboard development
* Data visualization
* Business intelligence
* Exploratory data analysis
* Turning raw data into actionable business insights

---

## 🚀 Future Improvements

Potential improvements to the dashboard include:

* Adding additional KPI cards
* Creating more advanced time-intelligence measures
* Adding year-over-year growth analysis
* Adding profit and margin analysis
* Creating a dedicated customer analysis page
* Creating a dedicated product analysis page
* Adding more advanced return-rate metrics
* Improving dashboard navigation and UX
* Adding additional business insights

---

This project was created as part of my journey into **Data Analytics and Business Intelligence**, with a focus on Power BI, SQL, data modeling, and data visualization.

---

⭐ If you found this project useful, feel free to explore the repository and the Power BI dashboard.
