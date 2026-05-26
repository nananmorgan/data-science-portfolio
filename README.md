# Data Science Portfolio

Portfolio of data science projects completed for academic and professional development. Presented as Jupyter notebooks, R Markdown files, interactive dashboards, and deployed applications.

*For more details on each project, click the project title to view the full repository with code, data, and documentation.*

---

## Machine Learning & Predictive Analytics

- **[Personality-Based Drug Use Prediction](https://github.com/nananmorgan/personality-drug-use-prediction)**: Investigated whether Big Five personality traits and demographics can predict drug use across stimulants, depressants, and hallucinogens. Built Logistic Regression and Random Forest classifiers with SMOTE and 5-fold stratified cross-validation. Best model achieved AUC-ROC of 0.867 for hallucinogen prediction.

  *Tools: Python, scikit-learn, imblearn (SMOTE), pandas, seaborn*

- **[Telecom Customer Churn: Segmentation & Prediction](https://github.com/nananmorgan/telecom-customer-churn)**: Built a two-stage pipeline combining K-Means clustering to segment customers into behavioral profiles with Logistic Regression to predict churn. Achieved 80% accuracy and AUC-ROC of 0.84.

  *Tools: Python, scikit-learn, pandas, seaborn*

- **[MLB Pitcher Injury Risk Prediction](https://github.com/nananmorgan/mlb-pitcher-injury-prediction)**: Developed a machine learning pipeline to predict pitcher injury risk using Statcast pitching data and injury records. Engineered features based on a 30-day pre-injury window methodology and trained Logistic Regression and Random Forest models.

  *Tools: Python, scikit-learn, pandas, pybaseball*

---
 
## Survival Analysis & Sports Analytics
 
- **[The Waiting Game: Survival Analysis of MLB Home Run Droughts](https://github.com/nananmorgan/mlb-tatis-hr-drought-analysis)**: Applied Cox Proportional Hazards modeling to quantify the statistical anomaly of Fernando Tatis Jr.'s 2026 home run drought using Statcast plate appearance data. Built Kaplan-Meier survival curves and a Cox model (concordance = 0.773) to show that his launch angle collapse (-82.6%) and barrel rate decline (-55.4%) predict a median drought more than twice his career baseline, while his exit velocity remained essentially unchanged. The model places the probability of his 180-PA drought at 3.96% even after adjusting for his 2026 profile.  
 
  *Tools: Python, lifelines, pybaseball, pandas, matplotlib, seaborn* 
 
--- 
  
## Data Analysis & Visualization

- **[Childcare Stipend ROI: A Data-Driven Business Case](https://github.com/nananmorgan/childcare-stipend-roi)**: Analyzed the National Database of Childcare Prices to quantify affordability gaps across CA and WA counties, built a priority matrix, and modeled ROI of employer-sponsored childcare stipends. Delivered via PowerPoint, a one-page executive brief, and an interactive Power BI ROI dashboard.

  *Tools: Python, pandas, matplotlib, Power BI*

- **[Climate Change Impact on Global Crop Yields](https://github.com/nananmorgan/climate-change-crop-yields)**: Analyzed the relationship between climate variables (CO2, temperature, precipitation) and crop yields for four major crops from 1961–2022. A log-transformed linear regression model achieved an adjusted R-squared of 0.947.

  *Tools: R, ggplot2, dplyr, tidyr*

- **[Wine Quality Statistical Analysis](https://github.com/nananmorgan/wine-quality-statistical-analysis)**: Comprehensive exploratory data analysis on the UCI Wine Quality dataset (6,497 wines). Applied Cohen's d, PMFs, CDFs, permutation testing, Pearson correlation, and multiple linear regression to identify quality predictors.

  *Tools: Python, statsmodels, scipy, thinkstats2, seaborn*

---

## Data Engineering & Generative AI

- **[COVID-19 Economic Impact: Multi-Source Data Integration](https://github.com/nananmorgan/covid19-economic-data-integration)**: Integrated three data source types — CSV flat file, REST API, and web-scraped tables — to examine COVID-19's impact on economic indicators. Cleaned, transformed, and merged all sources into a unified SQLite database.

  *Tools: Python, pandas, requests, BeautifulSoup, SQLite*

- **[Japanese Recipe Adaptation with Generative AI](https://github.com/nananmorgan/japanese-recipe-adaptation)**: Built and deployed a web app that adapts Western recipes to Japanese ingredients using GPT-based generation, a fine-tuned ingredient classifier, and a custom "recipe drift" scoring system.

  *Tools: Python, OpenAI GPT API, Streamlit, GitHub*

---

## Contact

If you have any questions or would like to discuss my work, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/nanamorgan) or email.
