# BrightQuery-Capstone-Project


In this project, we developed a confidence scoring system to evaluate global businesses. Our approach involved building a linear regression model trained on BrightQuery’s U.S. business data, using global features as inputs. This model was then applied to score international businesses, generating both absolute scores and relative scores segmented by country and industry.

The final deliverables include the linear regression scoring model saved as a .pkl file, along with an interactive dashboard for exploring the results.


## 📹 Demo

A screen recording of the project workflow is included in the repository

---

## 📊 Project Summary

### 1. 🧪 Initial Exploration & EDA
- Performed exploratory data analysis (EDA) to understand fill rates and identify trends in the early dataset.
- Initially attempted to join all data tables, but faced issues creating accurate joins that preserved data quality.

### 2. 🗂️ Data Selection & Feature Engineering
- Switched to **Crunchbase** as the primary dataset due to its rich global coverage of both U.S. and international businesses.
- Transformed categorical variables into binary indicators.
- Engineered custom features based on observed patterns and business characteristics.

### 3. 📈 Modeling
- Tested multiple regression models to predict U.S.-based business confidence scores.
- Selected **Linear Regression** for its interpretability and solid performance.

### 4. 🌐 Global Scoring
- Applied the trained linear regression model to score global businesses using the engineered features.

### 5. 📊 Dashboard Highlights
- Developed an interactive dashboard with:
  - **Absolute and relative scores** by country and industry.
  - **Feature importances** displayed for each score to enhance model transparency.
  - Filtering and comparison tools across business segments.



How to run this?
The attached ZIP file contains the Streamlit code and model. Running it and hosting it locally will launch the Streamlit dashboard, which generates the scores. Please refer to the included recording for navigation instructions.
