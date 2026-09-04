# 🚚 Supply Chain Delay Analytics

## 📊 Power BI Data Analytics Project

This project analyzes **supply chain and delivery performance** to understand why orders are delayed, how delivery performance changes over time, and where businesses may be losing money because of delays.

The goal of this project is to transform raw supply chain data into an **interactive Power BI dashboard** that helps businesses monitor important Key Performance Indicators (KPIs), identify delivery problems, and make data-driven decisions.

---

## 🎯 Project Objective

Supply chain companies handle thousands of orders every day. Delays in processing, transportation, and delivery can result in:

* Late deliveries
* Customer dissatisfaction
* Higher shipping costs
* SLA (Service Level Agreement) breaches
* Increased return rates
* Additional penalty costs
* Poor operational performance

The objective of this project is to analyze these problems using data and create a dashboard that provides a **clear overview of supply chain performance**.

### Main Questions I Wanted to Answer

1. How many orders were processed?
2. How many orders were delivered on time?
3. What percentage of orders breached the SLA?
4. How much was spent on shipping?
5. What is the average shipping cost per order?
6. Which regions have more orders?
7. How is order volume changing month by month?
8. What is the customer satisfaction level?
9. How many orders are considered high-risk?
10. How much penalty cost is associated with delayed orders?
11. Which areas of the supply chain require attention?

---

# 📁 Dataset

The project uses a supply chain dataset containing **20,000+ order records**.

The dataset contains information related to:

* Orders
* Customers
* Regions
* Shipping
* Delivery
* Processing
* SLA
* Costs
* Distance
* Weight
* Customer satisfaction
* Returns
* Risk levels

The raw dataset is included in this repository under the `Data` folder.

---

# 🛠️ Tools & Technologies

### Data Visualization

* **Microsoft Power BI**

### Data Preparation

* **Power Query**

### Data Analysis

* **DAX (Data Analysis Expressions)**

### Data Source

* **CSV**

### Documentation & Presentation

* Microsoft PowerPoint

---

# 🔄 Project Workflow

The project was completed through the following data analytics process:

```text
Raw Supply Chain Data
        ↓
Data Import
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Calculations
        ↓
KPI Development
        ↓
Data Visualization
        ↓
Business Insights
```

---

# 1️⃣ Data Import

I imported the raw supply chain dataset into **Power BI**.

The dataset contains more than **20,000 order records**, allowing the dashboard to provide a realistic view of supply chain operations.

---

# 2️⃣ Data Cleaning & Transformation

Before creating the dashboard, I prepared the raw data using **Power Query**.

The data preparation process included:

* Checking column data types
* Handling missing values
* Removing unnecessary data
* Cleaning inconsistent values
* Formatting date fields
* Creating useful calculated columns
* Preparing fields for analysis
* Ensuring the data was suitable for visualization

This step was important because dashboards are only reliable when the underlying data is clean and structured properly.

---

# 3️⃣ Data Modeling

After cleaning the data, I structured the data inside Power BI so that different dimensions and metrics could be analyzed effectively.

The model supports analysis across areas such as:

* Time
* Region
* Orders
* Delivery
* Shipping
* Cost
* Customer satisfaction
* Risk

This allows users to interact with the dashboard and analyze supply chain performance from different perspectives.

---

# 4️⃣ DAX Measures

I created multiple **DAX measures** to calculate important business KPIs.

Some of the major measures created include:

### 📦 Order Metrics

**Total Orders**

Measures the total number of orders in the dataset.

**Monthly Order Growth**

Tracks how order volume changes compared with previous months.

---

### 🚚 Delivery Metrics

**On-Time Delivery %**

Measures the percentage of orders delivered within the expected delivery time.

**SLA Breach Rate %**

Measures the percentage of orders that failed to meet the defined SLA.

**Return Rate %**

Measures the percentage of orders that were returned.

---

### 💰 Cost Metrics

**Total Shipping Cost**

Calculates the total amount spent on shipping.

**Average Shipping Cost / Order**

Calculates the average shipping cost associated with each order.

**Cost per KM**

Measures transportation cost relative to delivery distance.

**Cost per KG**

Measures transportation cost relative to shipment weight.

**Penalty Cost YTD**

Calculates the accumulated penalty cost for SLA-related issues during the year.

---

### ⚠️ Risk & Operations Metrics

**High Risk Orders %**

Measures the percentage of orders categorized as high-risk.

**Average Processing Days**

Measures the average number of days required to process orders.

---

# 5️⃣ Dashboard Development

After preparing the data and creating the DAX measures, I designed an interactive **Power BI dashboard**.

The dashboard provides a high-level summary of supply chain performance and allows users to explore the data interactively.

The Power BI project file is available in the repository.

---

# 📈 Dashboard KPIs

The dashboard focuses on important business KPIs such as:

| KPI                       | Purpose                                  |
| ------------------------- | ---------------------------------------- |
| Total Orders              | Understand overall order volume          |
| On-Time Delivery %        | Measure delivery performance             |
| SLA Breach Rate %         | Identify SLA failures                    |
| Total Shipping Cost       | Monitor transportation expenses          |
| Avg Shipping Cost / Order | Understand average order cost            |
| Return Rate %             | Monitor returned orders                  |
| Customer Satisfaction     | Understand customer experience           |
| High Risk Orders %        | Identify potentially problematic orders  |
| Penalty Cost YTD          | Monitor financial impact of SLA breaches |
| Cost per KM               | Analyze transportation efficiency        |
| Cost per KG               | Analyze shipment cost efficiency         |
| Avg Processing Days       | Measure operational efficiency           |

---

# 📊 Visual Analysis

The dashboard includes visualizations to understand:

### 📅 Monthly Order Trends

Shows how order volume changes over time.

This helps identify:

* Increasing demand
* Decreasing demand
* Seasonal patterns
* Changes in operational workload

### 🌎 Regional Analysis

Shows order distribution across different regions.

This helps identify regions with:

* Higher order volumes
* Potential delivery problems
* Higher operational activity

### 🚚 Delivery Performance

Analyzes whether orders are being delivered within the expected timeframe.

This helps identify potential delivery bottlenecks.

### 💰 Shipping Cost Analysis

Analyzes total and average shipping costs.

This can help businesses understand where transportation expenses are increasing.

### 😊 Customer Satisfaction

Analyzes customer satisfaction in relation to supply chain performance.

This helps connect operational performance with customer experience.

---

# 🔍 Key Business Insights

The dashboard is designed to help stakeholders quickly identify:

* Delivery performance
* SLA compliance
* Cost-related problems
* High-risk orders
* Regional differences
* Processing delays
* Customer satisfaction trends
* Return patterns

Instead of looking through thousands of individual records, decision-makers can use the dashboard to quickly identify areas that require attention.

---

# 💡 Business Value

This project demonstrates how raw operational data can be transformed into useful business information.

A supply chain manager could use this dashboard to:

### 🚚 Improve Delivery Performance

Identify areas where deliveries are frequently delayed and investigate the reasons.

### 💰 Control Shipping Costs

Monitor shipping expenses and identify areas where transportation costs are higher than expected.

### ⚠️ Identify High-Risk Orders

Monitor high-risk shipments and take preventive action before they become major problems.

### 😊 Improve Customer Experience

Analyze the relationship between delivery performance and customer satisfaction.

### 📊 Support Data-Driven Decisions

Use KPIs and interactive visualizations instead of relying only on manual reports.

---

# 📂 Repository Structure

```text
Supply-Chain-Delay-Analytics/
│
├── README.md
│
└── Supply Chain delay Projects/
    │
    ├── Asset/
    │   └── Dashboard assets and images
    │
    ├── Data/
    │   └── Supply Chain Dataset
    │
    ├── Power BI/
    │   └── New Supply Chain Delay Analysis.pbix
    │
    └── PPT/
        └── Project Presentation
```

The repository currently contains separate folders for the project assets, dataset, Power BI file, and presentation.

---

# 🎓 Skills Demonstrated

Through this project, I demonstrated practical experience in:

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Data Visualization
* Power Query
* Power BI
* DAX
* KPI Development
* Business Intelligence
* Dashboard Development
* Supply Chain Analytics
* Business Insights
* Data Storytelling

---

# 🚀 What I Learned

This project helped me understand how a real-world data analyst approaches a business problem.

I learned how to:

1. Understand a business problem
2. Work with raw data
3. Clean and transform data
4. Build meaningful metrics
5. Create DAX calculations
6. Design an interactive dashboard
7. Analyze business performance
8. Convert data into actionable insights
9. Present findings in a simple and understandable way

---

# 📌 Project Summary

**Supply Chain Delay Analytics** is a Power BI business intelligence project focused on understanding delivery performance, shipping costs, SLA compliance, operational efficiency, customer satisfaction, and order risk.

The project demonstrates the complete analytics workflow — from **raw data preparation to interactive dashboard development and business insights**.

### ⭐ Project Highlights

* **20,000+** supply chain orders analyzed
* **$1.1M+** shipping cost analyzed
* Multiple business KPIs developed using DAX
* Interactive Power BI dashboard
* Data cleaning and transformation using Power Query
* Regional, monthly, delivery, cost, and customer analysis
* Business-focused insights for supply chain decision-making

---

## 👨‍💻 Author

**Kishore Dharun**

Computer Science Engineering Graduate | Data Analyst

### Core Skills

`Power BI` `SQL` `Python` `Excel` `Power Query` `DAX` `Data Cleaning` `Data Visualization` `Business Analytics`

---

## ⭐ If you find this project useful

Feel free to explore the repository and review the Power BI dashboard, dataset, and project documentation.
