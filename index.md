# Portfolio

---
### Loan Default Detector

<center><img src="images/loan.gif" alt="" width="500"/></center>

(<a href="https://github.com/xfreppihs/loan-default-detector-xgboost-lightgbm-histgradientboosting" target="_blank">github</a>)(<a href="https://github.com/xfreppihs/streamlit-deploytment-on-GCP" target="_blank">deployment</a>)
- Built a Loan Default Detector to predict credit card applicants at risk of default. 
- Cleaned and analyzed 300,000 application records. Implemented multiple classification models (XGBoost, LightGBM, HistGradientBoosting), addressing class imbalance by integrating SMOTE and undersampling strategies.
- Orchestrated Hyperopt and MLflow for hyperparameter tuning, achieving a 0.24 PRC-AUC score from the final model, which improved 300% over the baseline, saving 41% charge-off loss (0.41 recall).
- Deployed the model on GCP with Streamlit for internal use, delivering insights for each application prediction.

---
### Supervised Contrastive Learning

<center><img src="images/SCL.png" alt="" width="500"/></center>

In my Deep Learning course group project (<a href="https://github.com/Dongzhikang/cs7643_deep_learning_project" target="_blank">github</a>) I replicated this Supervised Contrastive Learning <a href="https://arxiv.org/abs/2004.11362" target="_blank">paper</a>, compared different contrastive loss functions, and analyzed the impact of architecture modifications on network performance, with the hope that supervised contrastive learning can be applied to tabular data to learn informative embeddings. Here are my <a href="pdf/CS_7643_final_report.pdf" target="_blank">project report</a> and a <a href="projects/contrastive_loss.html" target="_blank">notebook</a> dissecting the math behind these loss functions.

---

### City Recommender

<center><img src="images/city.gif" alt="" width="500"/></center>

(<a href="https://youtu.be/mn9afg52erY" target="_blank">presentation</a>)(<a href="pdf/team032report.pdf" target="_blank">report</a>)
- Led a team of 6 to build a content-based interactive recommender system using weighted cosine similarity
- Scraped, merged, and cleaned ~30,000 US cities data with ~80 attributes from three different data sources
- Imputed missing values with k-nearest neighbors (KNN) and performed k-means clustering to evaluate data quality

---

### House price prediction

<center><img src="images/housing_wordcloud.png" alt="" width="500"/></center>

(<a href="pdf/house_report.pdf" target="_blank">report</a>)
- Scraped and cleaned ~1,000 local house price data from Zillow.com
- Built regularized linear regression (Lasso and Ridge) and random forest regression models to predict sales prices
- Performed feature engineering using natural language processing (NLP) and improved prediction mean squared error by 9%

---

### US presidential election prediction

<center><img src="images/election.png" alt="" width="500"/></center>

(<a href="https://youtu.be/6DYfaQmHcH8" target="_blank">presentation</a>)(<a href="pdf/team018finalreport.pdf" target="_blank">report</a>)
- Led a team of 5 to build regression (linear, random forest) and classification (decision trees, logistic) models to predict 2020 US presidential election outcomes using Census and past election data; achieving 7.1 RMSE for regression and 91.3% accuracy and 94.3% AUC for classification
- Examined trends in demographic factors from 2012 to 2020 and their correlations with election outcomes

---

### Non-linear regression curve fitting

<center><img src="images/drc_4PL.png" alt="" width="500"></center>

- Used four parameter logistic to study a dose-response curve and calculate the IC50/ED50/EC50 dose (<a href="projects/drc_4PL.html" target="_blank">R</a>)
- Used linear-quadratic and multi-target to model cell survival curve after radiation (<a href="projects/nls_lq_mt.html" target="_blank">R</a> &#124; <a href="projects/curve_fit_lq_mt.html" target="_blank">python</a>)
- Used exponential decay increasing to the max to fit a (pseudo) first-order reaction (<a href="projects/nls_exponential_decay_increasing_to_max.html" target="_blank">R</a> &#124; <a href="projects/curve_fit_exponential_decay_increasing_to_max.html" target="_blank">python</a>)

---

### Correlation analysis

<center><img src="images/correlation_analysis.png" alt="" width="500"/></center>

(<a href="projects/correlation_analysis.html" target="_blank">slides</a>)
- Analyzed correlations between redox-related metabolites in head and neck cancer patients and their responses to a cancer treatment
- Built a multiple linear regression model using the forward selection based on adjusted R<sup>2</sup> method

---

### Mouse tumor growth trend analysis

<center><img src="images/mouse_tumor.png" alt="" width="500"/></center>

- Recorded and graphed mouse xenograft tumor growth trend (<a href="projects/mouse_tumor_r.html" target="_blank">R</a> &#124; <a href="projects/mouse_tumor_py.html" target="_blank">python</a>)

---

### ATP Tennis Analytics

<center><img src="images/ATP_tennis.png" alt="" width="500"/></center>

(<a href="https://www.kaggle.com/iamanalien/atp-tennis-2000-2020-initial-analysis" target="_blank">kaggle notebook</a>)
- Analyzed over 63,000 men’s professional tennis matches from 2000 to 2020
- Examined the statistics on upset rate and the impact of winning the first set on the whole match
- Created interactive visualizations for top players’ ranking and performance comparisons

### Notes
- <a href="projects/tree_notes.html" target="_blank">regression tree &#124; random forest regression &#124; logistic regression notes</a>
- <a href="projects/pca_notes.html" target="_blank">PCA &#124; PCR notes</a>
- <a href="projects/stepwise_notes.html" target="_blank">stepwise &#124; lasso &#124; elastic net &#124; ridge regression notes</a>
- <a href="https://github.com/xfreppihs/machine-learning-data-science-notes/blob/main/python%20notes.ipynb" target="_blank">Python notes</a>
- <a href="https://github.com/xfreppihs/machine-learning-data-science-notes/blob/main/pandas_notes.ipynb" target="_blank">Pandas notes</a>
