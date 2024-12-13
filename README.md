# Water Pollutants Prediction Project

Welcome to the **Wastewater Pollutants Prediction** project repository! 🌊✨ This project explores the relationship between population growth and pollution levels of ammonia, phosphorus, and nitrate ions in wastewater, using data analysis and machine learning to forecast pollutant release amounts for future years.


---

## 📜 **Project Overview**

The goal of this project is to understand and forecast the release of ammonia, phosphorus and nitrate ion to wastewater based on provincial population and other contributing factors. Key aspects include:

- **Exploratory Data Analysis (EDA)** to uncover trends and patterns.
- **Data preprocessing** for machine learning applications.
- Building **predictive models** to estimate pollutant levels.

---

## 📊 **Dataset**

The dataset includes:

- **Pollutant information**: Estimation method, unit of measurement, release media and release quantities from year 2000 to 2022, and  chemical substances.
- **Pollutant sources**: Company name, facility name, geographical information.
- **Population statistics**: Provincial population from 2000 to 2022data over several years.


### Data Preparation:
- Cleaned missing values and handled outliers.
- Scaled data for uniformity.
- Prepared for machine learning analysis.

---

## 🔑 **Key Steps**

### 1️⃣ Exploratory Data Analysis (EDA)
- Visualized **population trends** alongside **pollutant levels**.
- Examined correlations between numerical features in dataset.
- Addressed **outliers** and **data inconsistencies**.

### 2️⃣ Data Preprocessing
- Normalized and scaled the dataset.
- Encoded categorical variables.
- Split data into **training** and **testing** sets.
- Pearson correlation and p-value for feature selection.

### 3️⃣ Machine Learning Modeling
Tested several models:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Polynomial Regressor**
Incorporated lag features for numerical features to capture historical trends to forecast future years.

#### Evaluation Metrics:
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- Mean Absolute Error (MAE)

**Best Model**: 🏆 *Random Forest Regressor* had the best performance for all three models

---

## 🧩 **Results**

- The **Random Forest Regressor** outperformed other models.
- Low RMSE and high R-squared values indicated high accuracy of forecasts.
  
- **Feature Importance Analysis** highlighted:
  - Regional/geopgraphical information as critical driver
  - Facility and company information as a significant contributor
  - Industrial activity as a significant contributor.

---

## ⚙️ **Dependencies**

This project uses **Python** and the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### Install Dependencies:
```bash
pip install -r requirements.txt
```

---

## 💻 **Usage**

### Reproduce the Analysis:
1. Clone the repository:
   ```bash
   git clone https://github.com/RuthOlasupo/pollution-population-trends.git
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook Water_Pollutants_Prediction.ipynb
   ```
3. Follow the steps in the notebook.

---

## 🚀 **Future Work**

- Add more datasets to explore diverse pollutants.
- Explore industry types and its effects on pollutant levels
- Incorporate **time-series analysis** for temporal trend modeling.
- Deploy the model as a **web application** for public use.

---

## 🤝 **Contributing**

Contributions are welcome! 💡 Open an issue or submit a pull request to collaborate.

---

## 📜 **License**

This project is licensed under the **MIT License**.

---

## 👩‍💻 **Author**

**Ruth Olasupo**

Connect with me on **[LinkedIn](https://linkedin.com)** or explore my **[portfolio](https://github.com/RuthOlasupo)**! 🎉
