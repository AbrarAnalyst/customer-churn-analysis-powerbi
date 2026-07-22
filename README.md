Customer Churn Analysis — Power BI Dashboard

 Overview
McKinsey-style interactive dashboard analyzing customer churn 
for Databel Telecom (6,687 customers, 26.9% churn rate).

Key Findings
- Month-to-month customers churn at 15x the rate of two-year contract holders
- Competitor offers drive 40%+ of all churn — not price or service quality
- Churn risk is highest in the first 12 months (48%), falling 80% by year 4
- California churns at 2x the rate of the next highest state
- Welch's t-test confirms churned customers pay significantly higher 
  monthly charges ($36.80 vs $28.91, t=18.96, p<0.001)

Tools & Methods
- Power BI Desktop
- DAX (calculated columns and measures)
- Welch's two-sample t-test
- Binary encoding of categorical churn label

Dataset
Databel Telecom customer dataset — 6,687 records, 29 variables