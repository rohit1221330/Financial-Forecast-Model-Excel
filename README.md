# 📊 Financial Forecast Model

## 📌 Project Overview

This project is a **financial forecasting and modeling analysis** built using historical business data. The model forecasts the financial performance of a multi-segment business across **Enterprise, SMB, and Consumer** segments for **2026–2027**.

The primary objective is to evaluate future **revenue growth, profitability, working capital requirements, cash flow generation, and overall business performance** under multiple operating scenarios.

---

## 🎯 Project Objectives

* Forecast Revenue and profitability for 2026–2027
* Analyze historical financial performance and key business drivers
* Evaluate Enterprise, SMB, and Consumer segment contributions
* Build Base, Upside, and Downside scenarios
* Forecast working capital requirements using DSO, DIO, and DPO
* Estimate future cash flow and closing cash balances
* Perform sensitivity analysis and Goal Seek
* Build an executive dashboard for management reporting

---

## 🛠️ Key Skills & Execution

### 1. Financial Modeling

Built a linked financial forecast model covering:

* Revenue
* COGS
* Gross Profit
* Operating Expenses
* EBIT
* Net Income
* Working Capital
* Cash Flow
* Closing Cash Balance

The model is structured so that changes in key assumptions flow through the financial statements and cash flow forecasts.

### 2. Historical Analysis

Analyzed historical financial data to identify:

* Revenue growth trends
* Gross margin trends
* Segment contribution
* Cost structure
* Working capital trends
* Historical business performance

These historical trends were used as the foundation for the forward-looking forecast assumptions.

### 3. Scenario Analysis

Created three forecast scenarios:

* **Base Case**
* **Upside Case**
* **Downside Case**

Excel `CHOOSE` functions were used to dynamically select assumptions based on the **Active Scenario**.

Changing the Active Scenario automatically updates the forecast outputs, including revenue, profitability, working capital, cash flow, and closing cash.

### 4. Working Capital Analysis

Built working capital schedules using:

* **DSO (Days Sales Outstanding)** → Accounts Receivable
* **DIO (Days Inventory Outstanding)** → Inventory
* **DPO (Days Payable Outstanding)** → Accounts Payable

The model estimates:

* Accounts Receivable
* Inventory
* Accounts Payable
* Net Working Capital
* Changes in Working Capital

### 5. Cash Flow Forecasting

Built a simplified cash flow model using:

* Net Income
* Depreciation
* Changes in Working Capital
* Capital Expenditure (Capex)

This model was used to estimate future **cash generation and closing cash balances** under different scenarios.

### 6. Sensitivity Analysis & Goal Seek

Used Excel **Goal Seek** and sensitivity analysis to understand how changes in key assumptions impact:

* Revenue
* Profitability
* Net Income
* Business targets
* Cash position

This helped identify the assumptions with the greatest impact on financial performance.

### 7. Dashboard & Reporting

Created an executive dashboard containing:

* Key financial KPIs
* Revenue and profitability trends
* Segment contribution
* Forecast outputs
* Scenario-based results
* Cash flow indicators

The dashboard is designed to provide management with a concise view of the company's financial outlook.

---

## 📈 Key Business Insights

### 1. Slowing Revenue Growth

Revenue growth is slowing, declining from approximately **6.0% in 2024 to 4.3% in 2025**.

This indicates that future growth assumptions are an important driver of the forecast and could have a significant impact on long-term profitability and cash generation.

### 2. Margin Improvement

Gross margin is projected to improve from approximately **38.8% in 2025 to 39.8% in 2027**.

This suggests potential improvement in the company's cost structure and operating efficiency.

### 3. Enterprise Segment Concentration

The **Enterprise segment contributes approximately 48% of total revenue**, making it the largest revenue contributor.

This creates an important business concentration risk, as changes in Enterprise performance could have a significant impact on overall company results.

### 4. Cash Flow Resilience

Even under the **Downside scenario**, the business remains cash-flow positive.

Projected 2027 closing cash remains comfortably above the **₹1.5 Cr minimum cash requirement**, indicating reasonable liquidity resilience under weaker operating conditions.

### 5. Base Case Forecast Outlook

Under the **Base Case**:

| Metric       |     2025 |     2027 |
| ------------ | -------: | -------: |
| Revenue      | ₹48.2 Cr | ₹56.7 Cr |
| Gross Margin |    38.8% |    39.8% |
| Net Income   |        — |  ₹6.3 Cr |

Revenue is projected to increase from approximately **₹48.2 Cr in 2025 to ₹56.7 Cr in 2027**, while Net Income reaches approximately **₹6.3 Cr**.

---

## 📊 Model Structure

The financial model broadly follows this structure:

```text
Historical Financial Data
          ↓
Historical Analysis
          ↓
Key Business Drivers
          ↓
Scenario Assumptions
(Base / Upside / Downside)
          ↓
Revenue Forecast
          ↓
COGS & Gross Profit
          ↓
Operating Expenses
          ↓
EBIT & Net Income
          ↓
Working Capital Schedule
(DSO / DIO / DPO)
          ↓
Cash Flow Forecast
          ↓
Closing Cash Balance
          ↓
Dashboard & Management Insights
```

---

## 🔄 Scenario Framework

| Scenario          | Purpose                                                   |
| ----------------- | --------------------------------------------------------- |
| **Base Case**     | Most realistic expected business performance              |
| **Upside Case**   | Stronger growth and/or improved operating performance     |
| **Downside Case** | Conservative assumptions with weaker business performance |

The **Active Scenario** controls the assumptions used throughout the forecast model.

---

## 💡 Key Financial Drivers

The forecast is primarily driven by:

* Revenue growth
* Segment-level performance
* Gross margin
* Operating expenses
* DSO
* DIO
* DPO
* Capex
* Depreciation
* Scenario assumptions

These drivers allow the model to dynamically reflect changes in business conditions.

---

## 🧰 Tools & Techniques

**Tools:**

* Microsoft Excel

**Techniques:**

* Financial Forecasting
* Financial Statement Modeling
* Scenario Analysis
* `CHOOSE` Functions
* Working Capital Modeling
* DSO / DIO / DPO Analysis
* Cash Flow Forecasting
* Sensitivity Analysis
* Goal Seek
* KPI Dashboarding
* Management Reporting

---

## 📌 Key Takeaways

* Revenue growth is moderating, making future growth assumptions critical.
* Gross margin is expected to improve through 2027.
* Enterprise is the largest revenue contributor and represents a key concentration risk.
* The business maintains positive cash flow even under the Downside scenario.
* The Base Case indicates continued revenue and profitability growth through 2027.
* Working capital and cash flow analysis provide additional visibility into the company's liquidity position.

---

## 🏆 Outcome

This project demonstrates practical skills in:

* **Financial Forecasting**
* **Financial Modeling**
* **Scenario Analysis**
* **Working Capital Management**
* **Cash Flow Forecasting**
* **Excel-Based Financial Analysis**
* **Sensitivity Analysis**
* **Goal Seek**
* **KPI Dashboarding**
* **Management Reporting**

The model provides a structured framework for evaluating **business performance, financial risks, profitability, liquidity, and scenario-based outcomes** to support management decision-making.

---

## 📂 Project Deliverables

The project can include the following files:

```text
Financial-Forecast-Model/
│
├── README.md
├── Financial_Forecast_Model.xlsx
├── Dashboard/
│   └── Executive_Dashboard.png
└── Documentation/
    └── Model_Assumptions.pdf
```

---

## 👤 Project Type

**Financial Modeling & Forecasting | Excel | Business Analysis | Scenario Planning**
