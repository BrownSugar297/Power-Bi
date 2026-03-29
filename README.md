# 📊 Power BI Dashboards Collection

A collection of **6 professionally designed Power BI dashboards** covering diverse business domains — from sales performance and HR analytics to cryptocurrency market tracking, automotive sales, fitness monitoring, and luxury watch retail. Each report is built with rich interactivity, slicers, and polished visuals tailored for real-world decision-making.

---

## 📁 Repository Structure

```
Power-Bi-main/
├── Car Dashboard.pbix               # Automotive sales performance tracker
├── Crypto Currency.pbix             # Cryptocurrency market cap & price analysis
├── HR  Analytics.pbix               # Employee attrition & workforce insights
├── Sales Analysis.pbix              # Regional & segment-wise sales analysis
├── Watch Dashboard.pbix             # Luxury watch retail sales & growth
├── fitness_tracker_app_design.pbix  # Personal fitness metrics app design
└── README.md
```

---

## 🗂️ Dashboard Overview

### 1. 🚗 Car Dashboard
**File:** `Car Dashboard.pbix` | **Pages:** 3

An automotive sales performance dashboard tracking sales against budget targets with year-over-year growth analysis.

| Metric | Details |
|---|---|
| **Pages** | 3 interactive pages |
| **Key Fields** | Sale, Budget, Pre-Sale, Growth, Category, Segment, Sub-Category, Sale Type, Order Date Year |
| **Visuals** | KPI Cards, Clustered Bar/Column Charts, Donut Chart, Advanced Slicer, Action Buttons |

**Highlights:**
- Budget vs. actual sales comparison with growth tracking
- Category and sub-category drill-down analysis
- Segment-level performance breakdown
- Navigation buttons for seamless page transitions

---

### 2. 💰 Crypto Currency
**File:** `Crypto Currency.pbix` | **Pages:** 2

A cryptocurrency market intelligence dashboard with historical price trend analysis and market capitalization tracking.

| Metric | Details |
|---|---|
| **Pages** | 2 interactive pages |
| **Key Fields** | Name, Market Cap, High Cap, Low Cap, Volume, Average, Open, Close, Low, High, Date (Day/Month/Quarter/Year) |
| **Visuals** | KPI Cards, Line Charts, Advanced Slicer, Action Buttons, Text Boxes |

**Highlights:**
- **Page 1 — Market Overview:** Market cap, high/low cap, average price trends over time
- **Page 2 — Price Analysis:** Open/close/high/low price movements, trading volume
- Date hierarchy filtering (day → month → quarter → year)
- Multi-coin comparison via slicer

---

### 3. 👥 HR Analytics
**File:** `HR Analytics.pbix` | **Pages:** 1

A human resources analytics dashboard focused on employee attrition, workforce demographics, and job satisfaction.

| Metric | Details |
|---|---|
| **Pages** | 1 comprehensive page |
| **Key Fields** | Attrition, Attrition %, Total Employee, Count of Attrition, Average Age, Average Salary, Avg Years At Company, Department, JobRole, Gender, EducationField, AgeGroup, JobSatisfaction, YearsAtCompany |
| **Visuals** | KPI Cards, Clustered Column Chart, Area Chart, Donut Chart, 100% Stacked Bar Chart, Advanced Slicer, Text Box |

**Highlights:**
- Overall attrition rate with employee count KPIs
- Department and job role attrition breakdown
- Gender and education field distribution
- Age group analysis with satisfaction scoring
- Average salary and tenure metrics

---

### 4. 📈 Sales Analysis
**File:** `Sales Analysis.pbix` | **Pages:** 2

A comprehensive retail sales analysis dashboard covering regional performance, customer segmentation, and product-level insights.

| Metric | Details |
|---|---|
| **Pages** | 2 interactive pages |
| **Key Fields** | Sales, Profit, Quantity, Discount, Region, State, Segment, Sub-Category, Order Date |
| **Visuals** | KPI Cards, Line Chart, Donut Chart, Pie Chart, Funnel Chart, Map, Bar Chart |

**Highlights:**
- **Page 1 — Overview:** Sales by region (donut), sub-category funnel, geographic map, sales trend line
- **Page 2 — Deep Dive:** Regional/segment breakdown with bar chart and map
- Four headline KPIs: Total Sales, Profit, Quantity, Discount
- US state-level geographic visualization
- Customer segment distribution (pie chart)

---

### 5. ⌚ Watch Dashboard
**File:** `Watch Dashboard.pbix` | **Pages:** 1

A luxury watch retail performance dashboard comparing 2022 vs. 2023 sales with growth analytics and regional breakdowns.

| Metric | Details |
|---|---|
| **Pages** | 1 comprehensive page |
| **Key Fields** | Sales, Budget 2023, Current Year Sales, YTD Sales 2022, YTD Sales 2023, Growth 22 vs 23, Total Growth by Segment, Total Growth of Category, Country, Region, Category, Segment, Customer Name, Month, Order Date (Month/Year) |
| **Visuals** | KPI Cards, Clustered Column Chart, Stacked Area Chart, Donut Chart, Slicer, Text Box, Shapes |

**Highlights:**
- YoY sales growth comparison (2022 vs. 2023)
- Budget vs. actual performance tracking
- Country and region-level breakdowns
- Segment and category growth analysis
- Monthly trend visualization with area chart

---

### 6. 🏃 Fitness Tracker App Design
**File:** `fitness_tracker_app_design.pbix` | **Pages:** 1

A mobile-style fitness tracker app designed in Power BI, showcasing personal health metrics with goal-tracking visualizations.

| Metric | Details |
|---|---|
| **Pages** | 1 app-style page |
| **Key Fields** | Avg Daily Steps, Avg Daily Calories, Avg Heart Rate, Total Exercise Sessions, Health Score, Calendar (Month/Quarter/Weekday/Year), User Name |
| **Visuals** | KPI Cards, Bar Chart, Line Chart, Donut Chart, Multi-Row Card, Slicer, Image, Bookmark Navigator |

**Highlights:**
- Health Score gauge with fill-to-100 visualization
- Target range tracking for steps, calories, heart rate, and sessions
- Weekday and calendar-based filtering
- App-style UI with custom SVG background
- Personalized welcome text per user

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Power BI Desktop** | Report creation and data modeling |
| **Power Query (M Language)** | Data transformation and ETL |
| **DAX (Data Analysis Expressions)** | Calculated measures and KPIs |
| **Custom Visuals** | Map visual (`basicMap`), Image visual (`simpleImage`) |
| **Power BI Themes** | CY24SU02, CY23SU04, Highrise, AccessibleDefault |

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free) — version **April 2024** or later recommended

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Power-Bi.git
   cd Power-Bi
   ```

2. **Open a report**
   - Launch **Power BI Desktop**
   - Go to **File → Open report**
   - Select any `.pbix` file from the repository

3. **Explore the dashboard**
   - Use slicers and filters on each page to interact with the data
   - Navigate between pages using the page tabs or action buttons

> **Note:** Some dashboards use embedded sample data within the `.pbix` file. No external data source connection is required to view the reports.

---

## 📌 Use Cases

| Dashboard | Ideal For |
|---|---|
| Car Dashboard | Automotive dealerships, sales managers tracking vehicle segment performance |
| Crypto Currency | Traders and analysts monitoring cryptocurrency trends and market cap |
| HR Analytics | HR departments analyzing workforce attrition and retention strategies |
| Sales Analysis | Retail businesses tracking regional and segment-level revenue and profit |
| Watch Dashboard | Luxury retail brands comparing sales performance YoY across regions |
| Fitness Tracker | Health app prototyping, personal wellness tracking UX demonstration |

---

## 📸 Screenshots

### 🚗 Car Dashboard
| | |
|---|---|
| ![Car Dashboard 1](screenshots/car-dashboard-1.png) | ![Car Dashboard 2](screenshots/car-dashboard-2.png) |

### 💰 Crypto Currency
| | |
|---|---|
| ![Crypto Currency 1](screenshots/crypto-currency-1.png) | ![Crypto Currency 2](screenshots/crypto-currency-2.png) |

### 👥 HR Analytics
| | |
|---|---|
| ![HR Analytics 1](screenshots/hr-analytics-1.png) | ![HR Analytics 2](screenshots/hr-analytics-2.png) |

### 📈 Sales Analysis
| | |
|---|---|
| ![Sales Analysis 1](screenshots/sales-analysis-1.png) | ![Sales Analysis 2](screenshots/sales-analysis-2.png) |

### ⌚ Watch Dashboard
| | |
|---|---|
| ![Watch Dashboard 1](screenshots/watch-dashboard-1.png) | ![Watch Dashboard 2](screenshots/watch-dashboard-2.png) |

### 🏃 Fitness Tracker
| | |
|---|---|
| ![Fitness Tracker 1](screenshots/fitness-tracker-1.png) | ![Fitness Tracker 2](screenshots/fitness-tracker-2.png) |

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve an existing dashboard or add a new one:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/new-dashboard`
3. Commit your changes: `git commit -m "Add: New Dashboard Name"`
4. Push to your branch: `git push origin feature/new-dashboard`
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋 Author

> Add your name and contact information here.

---

⭐ **If you find this repository useful, please give it a star!**
