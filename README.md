# Japanese Stock Market Analysis & Portfolio Optimization (Excel)

## 📌 Project Overview
This project presents a comprehensive financial and statistical analysis of companies listed on the Nikkei index (2015-2025). The primary goal was to analyze historical returns, evaluate statistical significance, and construct optimized investment portfolios using Modern Portfolio Theory (Markowitz) and the Single-Index Model.

## 🛠️ Tools & Technologies
* **Microsoft Excel:** Advanced Formulas (`LINEST`, Matrix operations), Data Analysis ToolPak, Conditional Formatting, Pivot Tables, Advanced Charting (Box & Whisker, Scatter, Line).

## 📊 Key Features & Methodology

### 1. Exploratory Data Analysis (EDA) & Seasonality
* Calculated daily/annual returns, descriptive statistics, quartiles, confidence intervals, and Value at Risk (VaR at 5%).
* Conducted seasonal analysis mapping returns across days of the week, months, and years using conditional formatting for rapid insight generation.
* Visualized data using Line charts, Box & Whisker plots, and comparative BoxPlots (e.g., best vs. worst performing stocks: NTT vs. Nissan).

### 2. Statistical Testing
* Performed **ANOVA** testing across all analyzed companies.
* Executed 1-tail and 2-tail **t-Student tests** comparing individual stock performance against the Nikkei index benchmark.

### 3. Portfolio Optimization (Markowitz Model)
* **2-Asset Portfolios:** Constructed Long-only and Long/Short portfolios utilizing correlation matrices. Calculated Expected Return ($R_p$), Portfolio Risk ($\Sigma_p$), and identified the Minimum Variance Portfolio (MVP).
* **Multi-Asset Portfolios:** Built 26 Long-only and 11 Long/Short portfolios using Variance-Covariance (VARP) matrices. 
* Visualized the **Efficient Frontier** plotted alongside individual assets and the Nikkei index.

### 4. Single-Index Model & Risk Decomposition (CAPM context)
* Calculated $\alpha$, $\beta$, and residual variance for all stocks using `LINEST` and Data Analysis regression tools.
* Decomposed total risk into **Systematic** and **Specific Risk** for each company.
* Evaluated a sample portfolio with randomized weights to determine aggregate $\alpha_p$, $\beta_p$, $R_p$, and risk profiles.
* Generated scatter plots with regression lines and trend equations for individual stocks.

## 🖼️ Project Gallery
<img width="954" height="286" alt="Markowitz" src="https://github.com/user-attachments/assets/720e9ec1-194d-42f7-aebe-2c6b223bcd4f" />
<img width="908" height="574" alt="Regresja" src="https://github.com/user-attachments/assets/78d924e7-5419-4825-8dfd-ee8ddec8f88d" />
<img width="1864" height="460" alt="Sezonowa" src="https://github.com/user-attachments/assets/1ea798e0-f58f-4467-9eee-32439bdf40ca" />
<img width="1870" height="860" alt="Statystyki opisowe+VaR" src="https://github.com/user-attachments/assets/0a0cc066-ada8-457f-9c16-9d677d7ad387" />
<img width="1235" height="280" alt="VARP" src="https://github.com/user-attachments/assets/b019ea09-10b8-4709-b662-33125713fc9b" />






