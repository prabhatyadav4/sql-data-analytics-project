# 📊 SQL Data Analytics Project

> A comprehensive collection of production-ready SQL scripts for data exploration, analytics, and business intelligence reporting.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Project Roadmap](#-project-roadmap)
- [Key Features](#-key-features)
- [Project Structure](#-project-structure)
- [Analysis Categories](#-analysis-categories)
- [Getting Started](#-getting-started)
- [Script Breakdown](#-script-breakdown)
- [Use Cases](#-use-cases)
- [Tech Stack](#️-tech-stack)
- [Learning Outcomes](#-learning-outcomes)
- [Acknowledgments](#-acknowledgments)
- [Contact](#-contact)

---

## 🎯 Overview

This repository demonstrates professional-grade SQL analytics techniques used by data analysts and BI professionals in production environments. It contains a complete suite of SQL scripts covering everything from initial database exploration to complex analytical reporting.

### What Makes This Different?

- ✅ **Production-Ready Scripts** — Battle-tested queries ready for real-world use
- ✅ **Best Practices** — Follows SQL optimization and coding standards
- ✅ **Comprehensive Coverage** — From basic exploration to advanced segmentation
- ✅ **Self-Documenting Code** — Clear naming conventions and comments
- ✅ **Modular Design** — Each script focuses on a specific analytical theme

---

## 🗺️ Project Roadmap

This project follows a comprehensive analytical framework designed by **[Data With Baraa](https://www.youtube.com/@DataWithBaraa)**, covering two main analytical paths:

  ![project_roadmap](https://github.com/user-attachments/assets/9e013d71-00e5-4351-817a-19f0ef04dc95)


### 📘 Exploratory Data Analysis (EDA) Path

The **blue path** focuses on understanding and profiling your data:

1. **Database Exploration** — Schema analysis and metadata discovery
2. **Dimensions Exploration** — Dimensional attributes and hierarchies
3. **Date Exploration** — Temporal boundaries and data coverage (2012-2015)
4. **Measures Exploration** — Key metrics and big numbers (999+)
5. **Magnitude Exploration** — Value distributions and outliers
6. **Ranking Exploration** — Top-N and Bottom-N performers

**Goal:** Build a solid foundation and understand what data you're working with.

---

### 📗 Advanced Analytics Path

The **green path** transforms insights into actionable business intelligence:

7. **Change-Over-Time Analysis** — Trends and temporal patterns
8. **Cumulative Analysis** — Running totals and moving metrics
9. **Performance Analysis** — KPI tracking and goal achievement
10. **Part-to-Whole Analysis** — Proportional and contribution analysis
11. **Data Segmentation** — Cohorts, clusters, and grouping strategies
12. **Reporting** — Customer and product analytics reports

**Goal:** Generate actionable insights and create stakeholder-ready reports.

---

### 🎯 The Complete Journey

```
Start → EDA (Understanding) → Advanced Analytics (Insights) → Business Value
```

This dual-path approach ensures you first **understand your data** thoroughly before diving into **advanced analytical techniques** that drive business decisions.

---

## ✨ Key Features

- 🔍 **Database Exploration** — Comprehensive data profiling and quality checks
- 📐 **Dimensional Analysis** — Deep dive into dimension tables and hierarchies
- 📅 **Time-Based Analytics** — Trend analysis and temporal patterns
- 📊 **Statistical Measures** — Aggregate functions and distribution analysis
- 🏆 **Ranking & Performance** — Top/bottom performers and percentile analysis
- 📈 **Change Detection** — Period-over-period comparisons and growth rates
- 🎯 **Cumulative Analytics** — Running totals and moving averages
- 🔄 **Part-to-Whole Analysis** — Contribution analysis and market share
- 👥 **Segmentation** — Customer and product grouping strategies
- 📋 **Business Reports** — Executive-ready customer and product insights

---

## 📂 Project Structure

```
sql-data-analytics-project/
│
├── scripts/
│   ├── 00_init_database.sql              # Database initialization and setup
│   ├── 01_database_exploration.sql       # Schema and metadata analysis
│   ├── 02_dimensions_exploration.sql     # Dimension table profiling
│   ├── 03_date_range_exploration.sql     # Temporal data boundaries
│   ├── 04_measures_exploration.sql       # Metric identification and stats
│   ├── 05_magnitude_exploration.sql      # Value distribution analysis
│   ├── 06_ranking_exploration.sql        # Top-N and ranking queries
│   ├── 07_change_over_time_analysis.sql  # Trend and growth analysis
│   ├── 08_cumulative_analysis.sql        # Running totals and aggregates
│   ├── 09_performance_analysis.sql       # KPI and performance metrics
│   ├── 10_part_to_whole_analysis.sql     # Contribution and composition
│   ├── 11_segmentation_analysis.sql      # Cohort and segment analysis
│   ├── 12_report_customers.sql           # Customer analytics report
│   └── 13_report_products.sql            # Product analytics report
│
├── LICENSE                                # MIT License
└── README.md                              # This file
```

---

## 📊 Analysis Categories

### 🔍 Exploratory Analysis (Scripts 01-03)

**Purpose:** Understand the data landscape before diving into analytics

- **Database Exploration** — Table structures, row counts, data types, and relationships
- **Dimensions Exploration** — Cardinality, uniqueness, and dimension hierarchies
- **Date Range Exploration** — Identify temporal boundaries and data completeness

**Key Questions Answered:**
- What tables exist and how are they related?
- What's the grain of each dimension?
- What time periods does the data cover?

---

### 📐 Measurement Analysis (Scripts 04-06)

**Purpose:** Identify and understand key business metrics

- **Measures Exploration** — Summary statistics (SUM, AVG, MIN, MAX, COUNT)
- **Magnitude Exploration** — Value distributions and outlier detection
- **Ranking Exploration** — Top performers, bottom performers, and percentile rankings

**Key Questions Answered:**
- What are the key metrics in the business?
- What's the distribution of values?
- Who are the top and bottom performers?

---

### 📈 Temporal Analysis (Scripts 07-08)

**Purpose:** Understand patterns and trends over time

- **Change Over Time** — Period comparisons, growth rates, YoY/MoM analysis
- **Cumulative Analysis** — Running totals, moving averages, year-to-date metrics

**Key Questions Answered:**
- How are metrics trending?
- What's the growth rate?
- What are the cumulative achievements?

---

### 🎯 Business Analysis (Scripts 09-11)

**Purpose:** Generate actionable business insights

- **Performance Analysis** — KPI tracking, goal attainment, variance analysis
- **Part-to-Whole Analysis** — Market share, contribution %, portfolio composition
- **Segmentation Analysis** — Customer segments, product categories, cohort analysis

**Key Questions Answered:**
- Are we meeting our targets?
- What's our market share?
- How can we segment our customers/products?

---

### 📋 Business Reporting (Scripts 12-13)

**Purpose:** Create stakeholder-ready analytical reports

- **Customer Report** — Customer lifetime value, retention, purchase patterns
- **Product Report** — Product performance, sales velocity, inventory insights

**Key Questions Answered:**
- Who are our most valuable customers?
- Which products drive the most revenue?
- What are the actionable recommendations?

---

## 🚀 Getting Started

### Prerequisites

- **SQL Server** (2019 or later recommended)
- **SQL Server Management Studio (SSMS)** or any SQL client
- Basic understanding of SQL and data analytics concepts

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/prabhatyadav4/sql-data-analytics-project.git
   cd sql-data-analytics-project
   ```

2. **Initialize the database**
   ```sql
   -- Run in SSMS
   -- Execute: scripts/00_init_database.sql
   ```

3. **Start with exploratory analysis**
   ```sql
   -- Execute scripts in order:
   -- 01_database_exploration.sql
   -- 02_dimensions_exploration.sql
   -- 03_date_range_exploration.sql
   ```

4. **Progress through analytical scripts**
   ```sql
   -- Continue with scripts 04-11 based on your analysis needs
   ```

5. **Generate business reports**
   ```sql
   -- Execute final reporting scripts:
   -- 12_report_customers.sql
   -- 13_report_products.sql
   ```

---

## 📝 Script Breakdown

### Foundation Scripts

| Script | Purpose | Key Techniques |
|--------|---------|----------------|
| `00_init_database.sql` | Database setup | CREATE DATABASE, table creation |
| `01_database_exploration.sql` | Schema analysis | Information schema queries, metadata |
| `02_dimensions_exploration.sql` | Dimension profiling | DISTINCT, cardinality checks |
| `03_date_range_exploration.sql` | Temporal boundaries | MIN/MAX dates, date gaps |

### Analytical Scripts

| Script | Purpose | Key Techniques |
|--------|---------|----------------|
| `04_measures_exploration.sql` | Metric statistics | Aggregate functions, grouping |
| `05_magnitude_exploration.sql` | Distribution analysis | Percentiles, quartiles, histograms |
| `06_ranking_exploration.sql` | Top-N analysis | ROW_NUMBER, RANK, DENSE_RANK |
| `07_change_over_time_analysis.sql` | Trend analysis | LAG, LEAD, period comparisons |
| `08_cumulative_analysis.sql` | Running calculations | Window functions, moving averages |
| `09_performance_analysis.sql` | KPI tracking | Goal vs actual, variance analysis |
| `10_part_to_whole_analysis.sql` | Composition analysis | Ratios, percentages, contribution |
| `11_segmentation_analysis.sql` | Cohort analysis | CASE statements, grouping strategies |

### Reporting Scripts

| Script | Purpose | Business Value |
|--------|---------|----------------|
| `12_report_customers.sql` | Customer analytics | CLV, retention, purchase behavior |
| `13_report_products.sql` | Product analytics | Revenue drivers, inventory optimization |

---

## 💼 Use Cases

This repository is perfect for:

- **Data Analysts** — Learning production SQL patterns for analytics
- **BI Professionals** — Building dashboards and reports
- **Data Engineers** — Understanding analytical requirements
- **Business Stakeholders** — Getting insights from data
- **Students** — Learning real-world SQL analytics techniques

### Industry Applications

- 🛒 **E-commerce** — Customer behavior and product performance
- 🏦 **Finance** — Portfolio analysis and risk metrics
- 🏥 **Healthcare** — Patient outcomes and operational efficiency
- 📦 **Supply Chain** — Inventory optimization and demand forecasting
- 🎯 **Marketing** — Campaign performance and customer segmentation

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Database** | Microsoft SQL Server |
| **Development** | SQL Server Management Studio (SSMS) |
| **Version Control** | Git & GitHub |
| **Documentation** | Markdown |

### Key SQL Techniques Used

- ✅ Aggregate Functions (SUM, AVG, COUNT, MIN, MAX)
- ✅ Window Functions (ROW_NUMBER, RANK, LAG, LEAD)
- ✅ Common Table Expressions (CTEs)
- ✅ Subqueries and Derived Tables
- ✅ JOINs (INNER, LEFT, CROSS)
- ✅ CASE Statements for Conditional Logic
- ✅ Date/Time Functions
- ✅ String Functions
- ✅ Statistical Functions (PERCENTILE, STDEV)

---

## 🧠 Learning Outcomes

Through this project, you'll master:

- ✅ **Exploratory Data Analysis (EDA)** — Systematic data profiling techniques
- ✅ **Statistical Analysis** — Distribution, central tendency, and variance
- ✅ **Time-Series Analysis** — Trends, seasonality, and growth rates
- ✅ **Business Analytics** — KPIs, segmentation, and performance metrics
- ✅ **SQL Best Practices** — Clean, efficient, and maintainable queries
- ✅ **Analytical Thinking** — Structured approach to data problems
- ✅ **Business Communication** — Translating data into actionable insights

---

## 🙏 Acknowledgments

This project was developed as part of the **Advanced Data Analytics** module from **[Data With Baraa](https://www.youtube.com/@DataWithBaraa)** — one of the best resources for practical SQL and data analytics education.

### Special Thanks to Baraa Khatib Salkini

**Why Baraa's Teaching Stands Out:**
- 🎯 **Real-World Focus** — Uses actual production patterns and business scenarios
- 📊 **Structured Approach** — Clear analytical frameworks (EDA → Advanced Analytics)
- 🛠️ **Tool Integration** — Shows how to use Draw.io for visualizations and Notion for project planning
- 💡 **Best Practices** — Emphasizes clean, maintainable, and optimized SQL code
- 🎓 **Project-Based Learning** — Hands-on projects that build portfolio-ready work

The dual-path analytical framework (Exploratory Data Analysis + Advanced Analytics) taught in this course has fundamentally changed how I approach data problems.

**📺 Check out his channel:** [Data With Baraa on YouTube](https://www.youtube.com/@DataWithBaraa)

*Highly recommended for anyone serious about data analytics and SQL mastery!*

---

## 👨‍💻 Contact

**Prabhat Kumar**  
Computer Science Engineering Student | Data Analytics & SQL Enthusiast

- 📧 Email: osrprabhatyadav4@gmail.com
- 💼 LinkedIn: [Prabhat Kumar](https://www.linkedin.com/in/prabhat-kumar-95059531a)
- 🐙 GitHub: [@prabhatyadav4](https://github.com/prabhatyadav4)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## ⭐ Show Your Support

If you found this project helpful:

- Give it a ⭐ on GitHub
- Fork it and experiment with your own analytics
- Share it with others learning SQL and data analytics

---

<div align="center">
  <sub>Built with analytical thinking and SQL mastery 💙</sub>
</div>
