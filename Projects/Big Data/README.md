# Big Data Analytics Projects

This folder contains projects demonstrating big data processing and analytics using distributed computing frameworks.

> **Disclaimer:** These notebooks are provided for portfolio demonstration only. Please do not copy or distribute without permission.

## Projects Overview

### Airbnb Data Science Analysis
**File:** `Airbnb_dataScience.ipynb`

A comprehensive end-to-end data science pipeline for Airbnb listing analysis using PySpark.

#### Features

**1. Data Ingestion**
- Real-time API integration with RapidAPI Airbnb endpoint
- JSON data loading and parsing with PySpark
- Performance monitoring (load time, memory usage, CPU utilization)

**2. Exploratory Data Analysis (EDA)**
- Schema inspection and data profiling
- Statistical summaries and distribution analysis
- Timestamp conversion and feature extraction

**3. Data Preprocessing**
- Missing value handling
- Feature encoding (StringIndexer, OneHotEncoder)
- Feature scaling (StandardScaler)
- Dimensionality reduction (PCA)

**4. Machine Learning Pipeline**
- **Regression Models:**
  - Random Forest Regressor
  - Linear Regression
  - Decision Tree Regressor
- Model evaluation using RegressionEvaluator
- Feature importance analysis

**5. Visualization**
- Interactive charts with Matplotlib and Seaborn
- Price distribution analysis
- Correlation heatmaps

## Technologies Used

- **PySpark** - Distributed data processing
- **PySpark ML** - Machine learning pipelines
- **REST APIs** - Data ingestion
- **Pandas** - Data manipulation
- **Matplotlib/Seaborn** - Visualization

## Getting Started

```python
# Initialize Spark Session
from pyspark.sql import SparkSession

spark = SparkSession.builder \
    .appName("Airbnb Data Analysis") \
    .getOrCreate()
```

## Requirements

- Python 3.8+
- PySpark
- pandas
- matplotlib
- seaborn
- requests
