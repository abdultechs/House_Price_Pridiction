# 🏠 House Price Prediction using Machine Learning

A machine learning project that predicts residential property prices based on key housing attributes such as square footage, bedroom and bathroom count, property condition, and geographic location. The notebook walks through exploratory data analysis (EDA), data visualization, and regression modeling using **Linear Regression** and **Gradient Boosting**.

---

## 📂 Project Structure

```text
├── housesales.ipynb     # Main Jupyter Notebook containing EDA and ML models
├── kc_house_data.csv    # King County house sales dataset
└── README.md            # Project documentation
```

---

## 📊 Dataset Overview

The project uses the **King County House Sales Dataset** (`kc_house_data.csv`), which includes historical property listings and features such as:

- **Property Details:** Number of bedrooms, bathrooms, and floors
- **Size Metrics:** Living area square footage, lot size, above-ground area, and basement square footage
- **Quality & Features:** Overall condition, grade, waterfront view, and construction/renovation years
- **Location Data:** Zipcode, latitude, and longitude coordinates
- **Target Variable:** Sale price of the house

---

## 🧠 Machine Learning Models

| Model | Role | Performance ($R^2$ Score) |
| :--- | :--- | :--- |
| **Linear Regression** | Baseline model to capture linear relationships between housing features and price | ~73.0% |
| **Gradient Boosting Regressor** | Ensemble tree-based model capturing complex, non-linear interactions | **~91.94%** |

---

## 📈 Exploratory Data Analysis & Visualizations

Key analytical insights explored in the notebook include:
- Distribution of properties by bedroom count
- Correlation between living area square footage and sale price
- Geographic price distribution across latitude and longitude
- Impact of structural features (waterfront access, number of floors, condition, and basement area) on property value

---

## 🛠️ Tech Stack & Libraries

- **Python 3.x**
- **pandas & NumPy** — Data manipulation and numerical operations
- **Matplotlib & Seaborn** — Statistical data visualization
- **scikit-learn** — Feature preprocessing, regression modeling, and evaluation

Install the required packages via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## 🚀 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/abdultechs/House_Price_Pridiction.git
cd House_Price_Pridiction
```

2. **Launch the Jupyter Notebook**

```bash
jupyter notebook housesales.ipynb
```

---

## 🎯 Key Takeaways

- End-to-end data preprocessing and exploratory data analysis on real estate data
- Feature selection and handling geographic/structural attributes
- Comparative performance evaluation between baseline linear models and ensemble boosting methods
- Achieving **91.94% accuracy** using `GradientBoostingRegressor`

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork this repository and experiment with additional algorithms (such as XGBoost, LightGBM, or Random Forests) or hyperparameter tuning.
