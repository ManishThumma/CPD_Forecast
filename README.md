# CPD_Forecast

**Project Overview: Forecasting CPD Crashes** – A Comprehensive Time Series Analysis
This project is a detailed time-series analysis focused on forecasting Cincinnati Police Department (CPD) crash reports using statistical and machine learning techniques. It is structured as a Quarto Markdown (QMD) document, blending code execution with a narrative to present a formal business report.

**Key Elements of the Project:**
Exploratory Data Analysis (EDA) and Time Series Decomposition:

Analyzing the characteristics of CPD crash data.
Identifying trends, seasonality, and patterns.
Preparing the dataset for advanced modeling.

**ARIMA Modeling:**
Conducting stationarity assessments and transformations.
Selecting the best ARIMA model using ACF/PACF analysis.
Evaluating model performance using AIC/BIC and residual diagnostics.

**Meta Prophet Model:**
Implementing the Prophet model to capture long-term trends and seasonal variations.
Tuning hyperparameters to optimize forecast accuracy.
Model Comparison and Validation:

**Performing rolling window cross-validation.**
Comparing the forecasting performance of SNaïve, SARIMA, and Prophet models.
Interpreting results to derive actionable insights.

**Project Inspiration & Purpose:**
The study aims to support data-driven decision-making for traffic safety improvements by providing accurate crash forecasts. The insights can assist in policy-making, resource allocation, and infrastructure planning.

**Methodology:**
**Data Source:** The dataset is derived from Cincinnati Open Data, focusing on traffic crash reports: 
**Tools Used: **The analysis employs R for statistical modeling and visualization.
**Presentation Format:** The report is formatted in Quarto (QMD), ensuring reproducibility, interactivity, and structured reporting.
