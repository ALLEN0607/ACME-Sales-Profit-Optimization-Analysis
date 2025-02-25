# ACME Sales & Profit Optimization Analysis

## **Introduction**
This project analyzes and optimizes the sales and profit of ACME's brands, **Aveda** and **Bobbi Brown**, based on given constraints and trends. The goal is to maximize sales and profit while ensuring business constraints are met.

## **Data Analysis**
- The dataset includes sales data segmented by **brand and product type**.
- Constraints include:
  - **Minimum and maximum contribution** per brand.
  - **Profit margins** and **trend-based growth limitations**.
- Data preprocessing was conducted to ensure proper formatting.

## **Optimization Process**
1. **Sales Normalization**: Adjust sales distribution to align with brand contributions.
2. **Profit Maximization**: Applied **constrained optimization** to maximize profit under margin constraints.
3. **Rolling Forecast**: Predicted sales over the next **5 years** under **baseline, optimistic, and pessimistic** growth scenarios.

## **Key Findings**
- **Optimized Sales & Profit**:
  - **Sales increased** across both brands while maintaining margin constraints.
  - **Profit grew significantly**, especially in high-margin product categories.
- **Future Growth Potential**:
  - A **5-year rolling forecast** indicates **steady growth** under current trends.
  - **Optimistic growth** scenarios show the potential for **higher returns** with strategic investments.

## **Visualizations**
📌 The following key insights are supported by visualizations:
1. **Total Sales Before and After Optimization**
2. **Sales per Segment Comparison**
3. **Total Profit Before and After Optimization**
4. **Profit per Segment Analysis**
5. **5-Year Rolling Sales Forecast**

## **5-Year Forecast**
- A predictive model using **compound annual growth rate (CAGR)** was applied:
  \[
  Future\ Sales = Current\ Sales \times (1 + Trend)^{Years}
  \]
- **Baseline Growth**: Sales increase following historical trends.
- **Optimistic Growth**: Sales increase at a **higher rate (+2%)**.
- **Pessimistic Growth**: Sales increase at a **lower rate (-2%)**.

## **Business Insights & Recommendations**
- **Strategic Investments**: Higher-margin segments should receive **additional marketing and sales efforts**.
- **Risk Management**: Market conditions could impact future growth; **monitor external factors**.
- **Sales Forecasting**: The **rolling forecast helps plan resource allocation** over the next five years.

## **How to Run the Code**
To execute this project:
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scipy

## Installation & Setup
### 1️ **Run in Google Colab**
You can open this project in **Google Colab** without installing anything:
1. Clone this repository to your Google Drive.
2. Open `ACME_Sales_Optimization.ipynb` in **Google Colab**.
3. Run the notebook **sequentially** (do not skip cells).
4. Results, visualizations, and analysis will be displayed.

### 2️ **Run Locally (Python)**
To run this project locally, follow these steps:

#### **1. Clone the repository**
```bash
git clone https://github.com/yourusername/ACME-Sales-Optimization.git
cd ACME-Sales-Optimization
