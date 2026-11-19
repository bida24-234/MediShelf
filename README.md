# MediShelf: Pharmaceutical Sales & Blood Demand Forecasting in Botswana Hospitals

## 1. Project Overview

MediShelf is a data analytics and forecasting project focused on improving pharmaceutical inventory management and blood supply planning in Botswana hospitals.

The project applies statistical analysis, time-series forecasting, and business intelligence techniques to historical pharmaceutical sales and blood demand data to identify patterns, forecast future demand, and support data-driven inventory decisions.

By combining predictive analytics with business intelligence, MediShelf aims to help healthcare institutions anticipate demand fluctuations, reduce potential stockouts, and improve resource allocation.

## 2. Problem Statement

Healthcare institutions must maintain adequate pharmaceutical and blood supplies to meet patient needs. However, inefficient inventory planning, fluctuating demand, and limited forecasting capabilities can contribute to:

- Pharmaceutical stockouts and overstocking.
- Inefficient allocation of medical resources.
- Challenges in anticipating blood demand.
- Increased inventory management costs.
- Difficulties in making evidence-based procurement decisions.

MediShelf explores how historical data and statistical forecasting methods can support better demand planning and inventory management.

## 3. Project Objectives

The project aims to:

1. Analyse historical pharmaceutical sales and blood demand patterns.
2. Identify trends, seasonality, and other demand-related patterns.
3. Apply statistical and time-series forecasting techniques to predict future demand.
4. Evaluate forecasting models using appropriate accuracy metrics.
5. Generate forecasts to support pharmaceutical inventory and blood supply planning.
6. Translate analytical findings into actionable business and operational recommendations through Power BI.

## 4. Datasets

The project consists of two analytical components:

### A. Pharmaceutical Sales Analysis

Historical pharmaceutical sales data covering multiple pharmaceutical product categories.

The analysis focuses on:
- Sales trends and patterns.
- Product-level demand behaviour.
- Temporal variations in pharmaceutical sales.
- Forecasting future pharmaceutical demand.

### B. Blood Demand Analysis

Historical blood-related data covering the period January 2020 to December 2024.

The analysis considers variables including:
- Historical blood usage.
- Blood donors available.
- Temperature.
- Relevant events.
- Predicted blood demand.

The objective is to understand demand patterns and develop forecasts that can support blood supply planning.

## 5. Methodology

The project follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework.

The analytical workflow includes:

1. **Business Understanding:** Identifying healthcare inventory and demand forecasting challenges.
2. **Data Understanding:** Exploring historical datasets and understanding their structure.
3. **Data Preparation:** Cleaning, transforming, and preparing data for analysis.
4. **Modelling:** Applying statistical and time-series forecasting techniques.
5. **Evaluation:** Comparing forecasting models using appropriate performance metrics.
6. **Deployment:** Presenting forecasts, insights, and recommendations through a Power BI dashboard.

## 6. Forecasting Techniques

Several statistical forecasting techniques are investigated and evaluated, including:

- Naive Forecasting
- Historical/Training Mean
- Simple Exponential Smoothing (SES)
- Moving Average
- Autoregressive Integrated Moving Average (ARIMA)
- Regression-based forecasting where appropriate

Model selection is based on comparative forecasting performance rather than assuming one model works best for every product or demand category.

## 7. Model Evaluation

Forecasting models are evaluated using statistical error metrics, including:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and forecasted values.
- **RMSE (Root Mean Squared Error):** Penalises larger forecasting errors more heavily.
- **MAPE (Mean Absolute Percentage Error):** Measures forecasting error as a percentage, where appropriate.
- **MASE (Mean Absolute Scaled Error):** Compares forecasting performance against a naive benchmark.

Rolling-origin evaluation and holdout testing are used to assess forecasting performance and model reliability.

## 8. Key Analytical Findings

The analysis demonstrates that forecasting performance varies across pharmaceutical categories and blood demand.

Some of the model selection findings include:

- Training Mean and Simple Exponential Smoothing performed competitively for blood demand forecasting.
- Different pharmaceutical categories required different forecasting approaches.
- Simple Exponential Smoothing, Moving Average, and Naive Forecasting were among the selected approaches for different pharmaceutical categories.
- Percentage-based metrics require careful interpretation, particularly when actual demand values are zero or relatively small.

These findings reinforce the importance of selecting forecasting models based on the characteristics of individual demand series.

## 9. Business Intelligence & Decision Support

The project incorporates Power BI to communicate analytical findings and support practical decision-making.

The dashboard is designed to present:

- Historical pharmaceutical sales trends.
- Blood demand patterns.
- Forecasted demand.
- Product-level forecasting insights.
- Inventory planning considerations.
- Key performance indicators.

The forecasting outputs are intended to support decisions such as:
- Identifying products that may require replenishment.
- Planning pharmaceutical procurement.
- Estimating future blood supply requirements.
- Considering safety stock and reorder levels.
- Improving resource allocation.

## 10. Tools & Technologies

| Tool / Technology | Application |
|---|---|
| Python | Data analysis and forecasting |
| Pandas | Data manipulation |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Exploratory data visualization |
| Statsmodels | Statistical modelling and time-series forecasting |
| Scikit-learn | Model evaluation and analytical support |
| Jupyter Notebook | Development and documentation |
| Power BI | Business intelligence and dashboard development |

## 11. Project Structure

```text
MediShelf/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_forecasting_models.ipynb
│   ├── 04_model_evaluation.ipynb
│   ├── 05_output_checks.ipynb
│   └── 06_pharma_training.ipynb
│
├── medishelf_dashboard.pbix
│
└── README.md
```

## 12. How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook.

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn jupyter
```

### Running the Notebooks

1. Clone the repository:

```bash
git clone https://github.com/bida24-234/medishelf.git
```

2. Navigate to the project directory:

```bash
cd medishelf
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the notebooks in numerical order and execute the cells.

5. Open the Power BI `.pbix` file using Microsoft Power BI Desktop to explore the dashboard.

**Note:** The datasets must be placed in their corresponding directories before running the notebooks. Large datasets may be excluded from the public repository.

## 13. Project Significance

MediShelf demonstrates how data analytics and statistical forecasting can be applied to real-world healthcare challenges.

The project combines descriptive, diagnostic, and predictive analytics to transform historical healthcare data into actionable insights.

Ultimately, it explores how data-driven forecasting can contribute to more informed pharmaceutical procurement, improved blood supply planning, and more efficient healthcare resource management in Botswana.

## 14. Author

**Kopo Lebo**

Business Intelligence and Data Analytics Student  
Botswana Accountancy College

**Areas of Interest:**
- Data Analytics
- Data Science
- Predictive Analytics
- Statistical Modelling
- Machine Learning
- Business Intelligence

GitHub: [bida24-234](https://github.com/bida24-234)

---

*This project was developed for academic and analytical purposes, demonstrating the application of statistical methods, forecasting techniques, and business intelligence in healthcare resource planning.*
