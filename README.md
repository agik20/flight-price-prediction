# ✈️ Flight Price Prediction Analysis

## 📋 Project Overview

This project provides a comprehensive analysis and predictive modeling of flight ticket prices using a dataset of over 300,000 flight booking records from India's top 6 metro cities, sourced from the **Ease My Trip** platform. The objective is to identify pricing patterns, understand airline pricing strategies, and build accurate predictive models for flight ticket prices.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## 🚀 Current Progress

| Phase | Status | Completion |
|-------|--------|------------|
| Data Collection & Cleaning | ✅ Completed | 100% |
| Exploratory Data Analysis | 🔄 In Progress | 40% |
| Feature Engineering | ⏳ Pending | 0% |
| Model Building | ⏳ Pending | 0% |
| Model Evaluation | ⏳ Pending | 0% |

**Current Status**: Dataset has been imported, cleaned, and validated. Exploratory Data Analysis (EDA) is currently underway.

## 📊 Dataset Description

### Source
The dataset was collected from **Ease My Trip** using the **Octoparse** web scraping tool, containing flight booking records from February 11 to March 31, 2022. Available at the following link: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction/data

### Specifications
- **Total Records**: 300,261 flight bookings
- **Features**: 11 attributes
- **Classes**: Economy and Business
- **Timeframe**: 50 days of data collection

### Feature Overview

| Feature | Description | Type |
|---------|-------------|------|
| **Airline** | Name of the airline (6 unique) | Categorical |
| **Flight** | Flight code | Categorical |
| **Source City** | Departure city (6 unique) | Categorical |
| **Departure Time** | Grouped time bins | Ordinal |
| **Stops** | Number of stops (0, 1, or 2+) | Ordinal |
| **Arrival Time** | Grouped time bins | Ordinal |
| **Destination City** | Arrival city (6 unique) | Categorical |
| **Class** | Economy or Business | Binary |
| **Duration** | Total travel time (hours) | Numerical |
| **Days Left** | Days until departure | Numerical |
| **Price** | Ticket price (target variable) | Numerical |

## 🔍 Research Questions

This analysis aims to address the following key questions:

1. **Airline Pricing Strategies**: How do ticket prices vary across different airlines?
2. **Booking Timing**: How are prices affected when tickets are purchased 1-2 days before departure?
3. **Temporal Effects**: How do departure and arrival times influence pricing?
4. **Route Analysis**: How do prices vary between different source and destination cities?
5. **Class Comparison**: What is the price differential between Economy and Business class?
6. **Stop Impact**: How does the number of stops affect ticket pricing?
7. **Duration Correlation**: What is the relationship between flight duration and price?

## 🛠️ Technical Implementation

### Tech Stack
- **Programming Language**: Python 3.8+
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: Scikit-learn, XGBoost, CatBoost, LightGBM
- **Development**: Jupyter Notebook, VS Code
- **Version Control**: Git, GitHub

### Project Structure
```
flight-price-prediction/
├── datasets/
│   ├── bussines.csv/        
│   ├── Clean_Data.csv/      
│   └── economy.csv/
├── main.ipynb
└── README.md
```

## 📈 Next Steps

### Immediate Actions
1. Complete comprehensive Exploratory Data Analysis (EDA)
   - Univariate and multivariate analysis
   - Correlation analysis between features
   - Price distribution across different dimensions
2. Identify and handle outliers in the target variable (Price)
3. Develop interactive visualizations for key insights

### Medium-term Goals
1. Implement feature engineering techniques:
   - Categorical variable encoding
   - Temporal feature extraction
   - Interaction features
2. Develop baseline predictive models:
   - Linear Regression
   - Random Forest
   - Gradient Boosting models (XGBoost, CatBoost, LightGBM)

### Long-term Objectives
1. Hyperparameter tuning and model optimization
2. Model interpretation and explainability analysis
3. Development of a predictive web application
4. Creation of a comprehensive analysis report

## 👥 Contributing

We welcome contributions to this project! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on how to:
- Report issues
- Suggest enhancements
- Submit pull requests

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Data sourced from **Ease My Trip**
- Web scraping performed using **Octoparse**
- Inspired by the need for transparent airline pricing information

---

**Note**: This repository will document the complete data science workflow from raw data acquisition to model deployment. Check back regularly for updates as the project progresses.

⭐ **Star this repo** to stay updated with our progress!
