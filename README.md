**🌍 Air Quality Prediction using PM2.5**

**📌 Project Overview**

Air pollution is one of the most critical issues in India, and PM2.5 (particulate matter ≤ 2.5 microns) is among the most harmful pollutants.
This project predicts PM2.5 concentration levels for Bangalore (2013–2018) using climatic and meteorological features such as temperature, rainfall, wind speed, and more.

We trained multiple machine learning regression models and deployed the best-performing model as a REST API using Flask.

**📊 Dataset**

**Climate Data Source**: Tutiempo.net

**PM2.5 Data Source**: Scraped via BeautifulSoup & merged with climate dataset

**Region**: Bangalore, India

**Years Covered**: 2013 – 2018

**Features (Independent Variables)**

**AT** → Average annual temperature

**TM** → Annual average maximum temperature

**Tm** → Annual average minimum temperature

**PP** → Annual precipitation (rain/snow)

**V** → Annual average wind speed

**RA** → Number of days with rain

**SN** → Number of days with snow

**Target Variable**

PM2.5 → Annual average particulate matter concentration

**🛠️ Technologies Used**

**Programming Language**: Python

**IDE**: PyCharm

**Notebook**: Google Colab (model training & testing)

**ML Models:**

Linear Regression

Ridge Regression

Lasso Regression

Support Vector Regressor (SVR)

Extra Trees Regressor

Decision Tree Regressor

**Backend**: Flask (REST API for predictions)

**⚙️ Methodology**

Data Collection → Web scraping with BeautifulSoup

Data Preprocessing → Cleaning, handling missing values, merging datasets

Exploratory Data Analysis (EDA) → Trends, correlations, visualizations

Model Training → Train-test split, multiple regression models applied

Model Evaluation → MSE, RMSE, R² comparison

Deployment → Best model exported as .pkl and served via Flask API

**📈 Results**

**Best Model**: (e.g., Extra Trees Regressor, R² ≈ 0.92)

**Key Findings**:

Wind speed & rainfall help reduce PM2.5 levels.

Temperature variations significantly influence PM2.5.

**🔮 Future Improvements**

Extending dataset with daily/hourly data

Adding more pollutants (PM10, NO₂, SO₂, O₃, CO)

Deploingy on cloud (Heroku / GCP / AWS)

Building a dashboard (Streamlit / Flask + React) for real-time monitoring
