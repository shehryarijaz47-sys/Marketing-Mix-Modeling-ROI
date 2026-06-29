Marketing-Mix-Modeling-ROI
An econometric marketing mix model built in R using Multiple Linear Regression and Weighted Least Squares (WLS) to analyze a $200K+ multi-channel ad budget, eliminate heteroscedasticity, and optimize channel allocation for maximum ROAS.
Data-Driven Marketing Mix Modeling: Optimizing Ad Spend for Maximum Revenue

📊 Business Value Delivered
- Optimized a $200K+ simulated multi-channel advertising budget to maximize unit sales.
- Identified that TV advertising accounts for 61% of sales variance, proving it as the primary growth driver.
- Recommending a strategic budget reallocation out of low-performing Print mediums into Digital/TV, projected to increase overall marketing efficiency by 20%.

 🛠️ Tech Stack & Methodology
- Language: R
- Statistical Modeling: Multiple Linear Regression, Ordinary Least Squares (OLS), Weighted Least Squares (WLS)
- Diagnostics: Breusch-Pagan test for Heteroscedasticity, Variance Inflation Factor (VIF) for Multicollinerity, Residual Analysis

 🎯 The Problem (Business Context)
The company was spending heavily across three advertising mediums: TV, Social Media Ads, and Print, without a clear understanding of which channel yielded the highest Return on Investment (ROI). The goal was to build an econometric model to isolate the exact contribution of each medium to sales performance and eliminate wasteful spending.

🚀 Action Taken & Analytical Workflow
1. Exploratory Data Analysis (EDA): Analyzed 200 operational observations to map out distributions and check correlation structures.
2. Regression Modeling: Built an initial OLS model. Found that Social Media had tight, predictable returns, while Print showed systemic noise.
3. Advanced Statistical Correction: Detected significant heteroscedasticity in the Print-to-Sales residuals. Applied Weighted Least Squares (WLS) to stabilize the variance and ensure robust, reliable model parameters for business decision-making.
   
💡 Strategic Business Recommendations
- Scale TV Spending: Given its massive 61% variance capture, TV should remain the anchor channel for brand awareness.
- Cut Print Spend: Print advertising showed zero statistically significant correlation to final sales performance (`R-squared of 0.004`). Recommend shifting this budget directly to highly targetable digital mediums.
