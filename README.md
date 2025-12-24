# ML Cinema Audience Forecasting Project

## 📌 Project Overview

In the competitive entertainment industry, predicting cinema attendance is crucial for optimizing resource allocation, scheduling, and marketing strategies. This project leverages Machine Learning to forecast audience turnout based on historical data, movie characteristics, and temporal factors.

Developed as part of a Business Data Management (BDM) framework, this project bridges the gap between raw transactional data and predictive business intelligence.

## 🎯 Objectives

* **Predictive Modeling**: Develop ML models to forecast movie-wise audience volume.
* **Feature Engineering**: Identify key drivers of cinema attendance (e.g., genre, timing, holiday impacts).
* **Business Insights**: Provide actionable recommendations for theater management to reduce operational waste and maximize revenue.
* **Accuracy Benchmarking**: Compare various algorithms (Regression, Random Forest, etc.) to find the most reliable forecasting tool.

## 🛠️ Tech Stack

* **Language**: Python 3.x
* **Data Manipulation**: `pandas`, `numpy`
* **Machine Learning**: `scikit-learn`, `XGBoost` (optional)
* **Visualization**: `matplotlib`, `seaborn`
* **Environment**: Jupyter Notebook / Google Colab

## 📊 Methodology

Following the data science lifecycle utilized in the Pizza Planet Case Study:

1. **Data Collection & Cleaning**: Handling missing values, removing duplicates, and standardizing movie metadata.
2. **Exploratory Data Analysis (EDA)**: Identifying seasonal trends (weekends vs. weekdays) and the impact of blockbusters.
3. **Preprocessing**: Encoding categorical variables (Genre, Rating) and scaling numerical features.
4. **Model Training**: Implementation of supervised learning models.
5. **Evaluation**: Assessing performance using metrics like MAE (Mean Absolute Error) and RMSE (Root Mean Square Error).


## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed. You can install the required dependencies via pip:

```bash
pip install -r requirements.txt

```

### Running the Project

1. Clone the repository:
```bash
git clone https://github.com/23f3000878/ML-Cinema-Audience-Forecasting-Project.git

```


2. Navigate to the notebooks directory and open the analysis file:
```bash
jupyter notebook notebooks/Cinema_Forecasting.ipynb

```



## 💡 Key Findings (Sample)

* **Temporal Influence**: Friday and Saturday evening shows account for over 60% of weekly revenue.
* **Genre Impact**: Action and Animation genres show the highest correlation with high-occupancy rates in local demographics.
* **Pricing Sensitivity**: Minor discounts on weekday morning shows significantly increased attendance in the "student" customer segment.

## 👤 Author

**Mohd Saalim** *Roll Number: 23f3000878* IIT Madras Online BS Degree Program

Indian Institute of Technology, Madras

---

*This project is part of a Business Capstone exploring the intersection of Data Science and Operational Efficiency.*
