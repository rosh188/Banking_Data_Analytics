# 📊 Stakeholder Insights & Performance Dashboard

An interactive **Tableau Business Intelligence dashboard** designed to provide a comprehensive view of stakeholder performance, insurer value creation, premium trends, profitability, policy tenure, and Assets Under Management (AUM).

The dashboard transforms complex insurance and stakeholder data into actionable insights, enabling decision-makers to compare insurers, analyse profitability, understand stakeholder contributions, and identify key business trends.

---

## 🎯 Project Objective

The objective of this dashboard is to provide stakeholders and decision-makers with a centralized view of important business and insurance performance metrics.

The dashboard helps answer questions such as:

- Which insurer has created the highest value?
- How are premium collections changing over time?
- How is shareholding distributed among stakeholders?
- What is the relationship between cost ratio and profitability?
- Which cities and policy tenures generate the highest profitability?
- How are Assets Under Management distributed across stakeholders?
- What is the total value created from Equity Assets Under Management?

---

## 📈 Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

| KPI | Description |
|---|---|
| 💰 Total Premium Collected | Total premium collected across all policies |
| 👥 Average Stakeholder Age | Average age of stakeholders |
| 📊 Equity AUM Value Created | Total value created where AUM is classified as Equity |
| 🏆 Highest Value Created | Highest value created by a single insurer |

All KPIs dynamically update based on the selected filters.

---

## 📊 Dashboard Visualizations

### 1. Insurer Value Creation

Compares the total value created by different insurers and highlights the highest-performing insurers.

### 2. Premium Collection Trend

Shows the trend of premiums collected over time to identify growth patterns and changes in premium performance.

### 3. Shareholding Distribution

Displays the distribution of shareholding among stakeholders to understand ownership and stakeholder contribution.

### 4. Cost Ratio vs. Profitability

Analyses the relationship between cost ratio and profitability to identify performance patterns and potential cost impacts.

### 5. City-wise Profitability

Compares profitability across different cities to identify high-performing and underperforming regions.

### 6. Policy Tenure vs. Profitability

Analyses profitability across different policy tenure durations to understand how policy duration impacts performance.

### 7. Assets Under Management

Visualizes the distribution of Assets Under Management across stakeholders and provides insight into asset allocation.

---

## 🎛️ Filters

The dashboard provides interactive filters for detailed analysis:

- 📍 **City** - Filter data by geographical location
- 👤 **Stakeholder** - Analyse individual stakeholder contributions
- ⏳ **Policy Tenure** - Use a range slider to select policy tenure
- 📅 **Date Range** - Analyse data within a specific time period
- ⚥ **Gender** - Filter stakeholders based on gender

All charts and KPIs dynamically respond to the selected filters.

---

## 🖱️ Interactivity

The dashboard provides an interactive analytical experience.

### 🔄 Dynamic Cross-Filtering

Selecting a data point in one visualization dynamically filters the other visualizations.

### 💡 Interactive Tooltips

Hover over charts and data points to view additional details and business metrics.

### 📊 Dynamic KPIs

KPI values automatically update according to the selected filters and dashboard interactions.

### 🎚️ Policy Tenure Range Slider

Users can select a specific policy tenure range to analyse profitability and performance.

---

## 📄 PDF Export

The dashboard includes a dedicated **PDF Export** option for reporting and offline analysis.

The exported PDF is designed to include:

- Key Performance Indicators
- Charts and visualizations
- Applied filters
- Dashboard insights
- Company branding/watermark

This allows stakeholders to easily share dashboard results in business reviews and management reports.

---

## 🔐 User Access & Security

The dashboard is designed to support **role-based data visibility**.

Different users can be provided with different levels of access depending on their role and responsibilities.

Example access structure:

| Role | Access Level |
|---|---|
| 👑 Admin | Full dashboard and dataset access |
| 📊 Management | Organization-wide performance |
| 🏢 Insurer | Relevant insurer and policy performance |
| 👤 Stakeholder | Stakeholder-specific information |
| 🌍 Regional User | Assigned city/region data |

Role-based access can be implemented when deploying the dashboard through Tableau Server or Tableau Cloud.

---

## 🛠️ Tools & Technologies

### Visualization & Analytics

- **Tableau**
- Tableau Calculated Fields
- Tableau Parameters
- Tableau Filters
- Tableau Dashboard Actions
- Tableau Tooltips

### Data Analysis

- Insurance data
- Stakeholder information
- Insurer performance
- Premium data
- Policy information
- Profitability metrics
- Assets Under Management

### Version Control

- Git
- GitHub

---

## 📁 Project Structure

```text
Stakeholder-Insights-Performance-Dashboard/
│
├── Tableau/
│   └── Stakeholder_Insights_Performance_Dashboard.twbx
│
├── Data/
│   └── dataset.csv
│
├── Images/
│   └── dashboard-preview.png
│
├── Documentation/
│   └── dashboard-requirements.md
│
└── README.md
