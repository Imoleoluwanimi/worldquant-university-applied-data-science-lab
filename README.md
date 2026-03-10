# Applied Data Science Lab — WorldQuant University

### 8 End-to-End Data Science Projects | ETL Pipelines | Machine Learning | Web App Deployment


## Overview

The Applied Data Science Lab at WorldQuant University is an intensive, project-based program consisting of 8 end-to-end data science projects. Each project simulates a real-world data science workflow from raw data ingestion to model deployment. Core themes across all projects include ETL pipelines, supervised and unsupervised machine learning, statistical analysis and web application development and deployment.

> *Due to WQU's Copyright License and Policies, course notebooks cannot be published. This README summarizes the skills and techniques covered across all 8 projects.*

[View Credential on Credly](https://www.credly.com/badges/6c2b3150-8fcc-4c08-8596-1967b22dc4ec/public_url)

---

## Projects Summary

---

### 1 & 2 — Housing in Mexico and Buenos Aires
*Supervised Learning | Linear Regression | Feature Engineering*

- Imported and merged multiple CSV files into pandas DataFrames using automated loops
- Performed EDA using histograms, scatter plots, boxplots and bar charts to understand feature distributions
- Assessed relationships between variables using Pearson correlation coefficients
- Built custom `wrangle` functions to clean and preprocess raw housing data
- Constructed end-to-end ML pipelines using `Ridge`, `OneHotEncoder`, `SimpleImputer` and `LinearRegression` from sklearn
- Applied L2 Regularization to prevent overfitting in linear models
- Built an interactive prediction dashboard using `ipywidgets` where users could adjust input features and see real-time model predictions

---

### 3 — Air Quality Forecasting in Nairobi
*Time Series | ARMA | MongoDB*

- Connected to a **MongoDB** database using `pymongo` to fetch unstructured time series data — my first experience working with NoSQL and JSON-like data structures
- Applied rolling averages, autocorrelation and lag operations to prepare time series variables
- Built and interpreted **Partial and Autocorrelation Function (PACF/ACF)** plots to identify model parameters
- Constructed **Autoregressive (AR) and ARMA models** using `statsmodels` and validated them via Walk Forward optimization
- Tuned lag observations and moving average window size using `GridSearchCV`

---

### 4 — Earthquake Damage Prediction in Nepal
*Classification | Decision Trees | SQL | Ethics in ML*

- Connected to a **SQL database** and queried data using `sqlite3` and magic commands
- Built classification pipelines using `OrdinalEncoder`, `DecisionTreeClassifier` and `LogisticRegression`
- Evaluated Decision Tree models using **Gini importance** for feature interpretation
- Assessed Logistic Regression predictions using **Odds Ratios**
- Explored the **ethics of machine learning** — specifically how data biases can lead to unfair environmental and social outcomes in model predictions

---

### 5 — Bankruptcy Prediction in Poland
*Imbalanced Classification | Random Forest | Gradient Boosting*

- Handled severe class imbalance using both **Undersampling and Oversampling** techniques
- Built ML pipelines using `SimpleImputer`, `RandomForestClassifier` and `GradientBoostingClassifier`
- Applied **k-fold Cross Validation** for robust model evaluation
- Tuned hyperparameters using `GridSearchCV`
- Built **interactive confusion matrices** to visualize how adjusting the model's probability threshold affects accuracy, precision and recall — a key lesson in balancing business tradeoffs

---

### 6 — Customer Segmentation in the US
*Unsupervised Learning | K-Means Clustering | PCA | Dash Deployment*

- Performed EDA on a **Survey of Consumer Finances** dataset with 28,000 observations and 350 features
- Built and fit **K-Means clustering models** to segment customers based on multiple features
- Selected optimal cluster count by evaluating variance, inertia and silhouette scores
- Applied **PCA (Principal Component Analysis)** to reduce feature dimensionality before clustering
- Developed and **deployed a Dash web application** structured in 3 layers (Business, Service and Presentation) with interactive scatter plots and bar charts controlled by sliders

---

### 7 — A/B Testing at WorldQuant University
*Statistical Testing | OOP | MongoDB | Web App Deployment*

- Fetched synthetic experimental data from **MongoDB** using `pymongo` queries
- Designed OOP class definitions containing database attributes and ETL methods based on experimental hypotheses
- Performed **cross-tabulation** and computed **odds ratios** from contingency tables
- Conducted **Chi-Square tests** using `statsmodels` to analyze experimental results
- Built and deployed a **3-tier interactive web application** with demographic, experiment and results sections featuring dropdowns, sliders, bar charts and choropleth maps

---

### 8 — Volatility Forecasting in India
*GARCH Models | API Development | FastAPI | OOP | TDD*

- Applied **defensive programming** when designing functions to fetch financial data from external APIs
- Used **Test Driven Development (TDD)** practices to build the following OOP objects:
  - `AlphaVantageAPI` class to programmatically fetch market data from an API
  - `SQLRepository` class to load and extract data into and from a SQLite database
- Built and fit **GARCH models** for financial volatility forecasting
- Created a `GarchModel` class with methods for data wrangling, model training, prediction generation and model saving
- Built and **deployed a REST API** using **FastAPI** and `uvicorn` with dedicated paths for model fitting and prediction serving

---

## Skills & Tools Gained

| Category | Tools & Techniques |
|----------|--------------------|
| Data Wrangling | pandas, NumPy, custom wrangle functions |
| Databases | MongoDB (pymongo), SQL (sqlite3) |
| Machine Learning | scikit-learn, Ridge, Logistic Regression, Decision Trees, Random Forest, Gradient Boosting |
| Time Series | ARMA, AR models, ACF/PACF, Walk Forward Validation |
| Unsupervised Learning | K-Means Clustering, PCA |
| Statistical Analysis | Pearson Correlation, Chi-Square Tests, Odds Ratios, A/B Testing |
| Imbalanced Learning | Oversampling, Undersampling |
| Web Development | Dash, FastAPI, ipywidgets, uvicorn |
| Software Engineering | OOP, Test Driven Development, Defensive Programming |
| Visualization | Matplotlib, Seaborn, interactive dashboards |

---

### Certificate

[WorldQuant University — Applied Data Science Lab](https://www.credly.com/badges/6c2b3150-8fcc-4c08-8596-1967b22dc4ec/public_url)



## Author

Delight Abioye
Data Scientist | WQU Applied Data Science Lab Graduate
