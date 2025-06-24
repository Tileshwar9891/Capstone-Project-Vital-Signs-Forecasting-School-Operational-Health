# Capstone-Project-Vital-Signs-Forecasting-School-Operational-Health

## Executive Summary

The Archdiocese of Seattle’s Office of Catholic Schools in Western Washington faces critical challenges in ensuring long-term operational viability across its educational network. The current planning approach relies heavily on historical data analysis, providing retrospective insights that result in reactive rather than proactive decision-making strategies. This reactive model limits administrators’ ability to anticipate and address emerging financial challenges, capacity constraints, and enrollment fluctuations before they threaten institutional sustainability. Without predictive capabilities, schools struggle to implement early interventions for financial distress, optimize facility utilization, and strategically allocate resources across the system.

## The Solution

This data science project analyzed five years of Catholic school operational data (2018–2022) combined with demographic datasets from Census.gov and educational performance metrics from Washington State. A meta-analysis feature selection methodology integrated Spearman correlation analysis, ANOVA F-tests, and permutation importance to identify consensus predictive factors while minimizing overfitting risks in small sample datasets.

Three classification models — Naive Bayes baseline, Random Forest, and Linear Discriminant Analysis — were developed for financial health classification (deficit, balanced, surplus status) and capacity utilization forecasting (high versus standard capacity). Models employed temporal validation using 2018–2021 training data and 2022 holdout testing to ensure reliable performance. The Multinomial Logit Model emerged as the optimal solution, delivering 69.09% accuracy for financial health prediction and 65.5% for capacity utilization while maintaining strong generalization with overfitting gaps below 8%.

Critical findings revealed that community demographic characteristics significantly outperform traditional educational metrics as financial health predictors, while academic performance indicators strongly correlate with capacity utilization patterns. Additionally, geospatial mapping with **ArcGIS** enhanced insights into demographic and geographic drivers of school viability.

## Impact

This predictive framework transforms reactive institutional planning into proactive strategic management through data-driven early warning systems. The robust meta-analysis methodology ensures reliable predictions despite small sample limitations, providing administrators with trustworthy operational intelligence.

Catholic school leaders can now:

- Anticipate financial distress before crisis points  
- Implement targeted community engagement strategies based on demographic risk factors  
- Optimize facility investments using evidence-based enrollment demand forecasting  
- Deploy intervention resources strategically across the educational network  
- Access comprehensive **Power BI dashboards** and **ArcGIS visualizations** offering location-specific insights for strategic decisions

This comprehensive analytical capability preserves educational excellence while ensuring long-term institutional sustainability across Western Washington’s diverse communities.

---

## Confidentiality Notice

Due to data privacy agreements, raw datasets and detailed school-level results are not included in this repository. This repository provides reproducible code and a high-level project overview only.

---

## Technologies Used

- **Languages & Libraries**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **Statistical Methods**: Spearman Correlation, ANOVA F-tests, Permutation Importance  
- **Machine Learning Models**: Naive Bayes, Random Forest, Linear Discriminant Analysis, Multinomial Logistic Regression  
- **Data Sources**: Census.gov demographic data, Washington State educational performance metrics  
- **BI & Visualization Tools**: Power BI, ArcGIS

---

## Contact

📧 tileshwarnarayan@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/tileshwar-narayan/)  
🐙 [GitHub](https://github.com/Tileshwar9891)

---

“Turning complex data into simple, actionable insights.”

