🏙️ Abbott Districts and Public Welfare — Research Project

📘 Overview

This project analyzes the Abbott districts of New Jersey to explore the relationship between demographic characteristics, socio-economic indicators, and public welfare outcomes.
Using U.S. Census data, this study identifies key trends across impoverished school districts and provides data-driven insights for improving local economies and social conditions.

The analysis combines exploratory data analysis (EDA), predictive modeling, and time series forecasting to quantify economic disparities and evaluate the impact of demographic variables on economic well-being.

🎯 Objectives

Analyze demographic and economic data for Abbott-designated districts in New Jersey.

Identify correlations between income, education, population demographics, and public welfare.

Build and compare predictive models to forecast economic performance and improvement trends.

Provide actionable insights to inform policy recommendations and community development initiatives.

🧮 Methodology
1. Data Collection

Data sourced from the U.S. Census Bureau and state-level education and income datasets.

Cleaned, merged, and standardized datasets for longitudinal analysis.

2. Data Analysis

Statistical correlation and multivariate regression to explore relationships among features.

Feature engineering for key demographic and temporal indicators.

3. Modeling Techniques
Model	Purpose	Notes
Linear Regression (with interactions)	Measure linear influence of demographics on economic outcomes	Highlights cross-variable effects
K-Nearest Neighbors (KNN)	Non-parametric pattern discovery	Captures local variations
Random Forest (Time Series)	Predict long-term economic trends	Demonstrated highest historical accuracy
4. Evaluation

Models assessed via cross-validation, historical fit, and forecast precision metrics.

Random Forest outperformed others in predicting income and employment trends.

📊 Key Findings

Strong correlations between education levels, median income, and poverty rates.

Demographic composition significantly impacts economic mobility and public welfare outcomes.

Time-series models suggest consistent underperformance of certain districts despite state funding parity.

Identified actionable factors for economic upliftment, including education access and infrastructure investment.

🧠 Technologies Used

Python

pandas, numpy, matplotlib, seaborn for EDA & visualization

scikit-learn for modeling and validation

statsmodels for regression and inference

Jupyter Notebook for documentation and reproducibility

U.S. Census API / CSVs for demographic data

🗂️ File Description
File	Description
Abbot_Districts.ipynb	Main notebook with data analysis, visualizations, and model results
data/	Contains cleaned or raw CSVs used for analysis (not uploaded for privacy)
README.md	Project documentation (this file)
⚙️ How to Run

Clone this repository

git clone https://github.com/yourusername/Abbott-Districts-Research.git
cd Abbott-Districts-Research


Install dependencies

pip install -r requirements.txt


Launch Jupyter Notebook

jupyter notebook


Then open Abbot_Districts.ipynb.

📈 Results Summary
Model	R² Score	MSE	Notes
Linear Regression	0.71	Moderate	Captured linear trends
KNN	0.76	Better local fit	Sensitive to neighborhood size
Random Forest	0.89	Lowest Error	Best overall performance
🧩 Future Work

Extend analysis to non-Abbott districts for comparative study

Incorporate education quality metrics and funding data

Apply causal inference methods to explore policy effects

Build an interactive dashboard for district-level insights

📜 Citation

If you use this research or data in your work, please cite as:

Sinha, A. (2024). Abbott Districts and Public Welfare: A Data-Driven Study of New Jersey’s Socio-Economic Landscape.

🪶 License

This project is released under the MIT License.
You are free to use, modify, and distribute with appropriate credit.
