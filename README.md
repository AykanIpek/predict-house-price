# 🏠 predict-house-price

This project applies machine learning to predict **average house prices in London** using two datasets (monthly and yearly). The project showcases skills in **data preprocessing, exploratory data analysis (EDA), predictive modeling, and hyperparameter tuning**.

---

## 📂 Project Structure

```
📁 predict-house-price
│── data/                # Monthly and yearly datasets
│── notebooks/           # Jupyter notebooks for EDA and modeling
│── src/                 # Python scripts for preprocessing & modeling
│── results/             # Model outputs, plots, and reports
│── README.md            # Project documentation
```

---

## 🔑 Key Stages

### 1. Data Processing
- Cleaned and preprocessed datasets
- Handled missing values and duplicates
- Encoded categorical variables
- Merged monthly and yearly features

### 2. Data Exploration (EDA)
- Analyzed feature distributions
- Identified correlations between house prices and features (income, interest rates, population, etc.)
- Visualized trends with **Matplotlib** and **Seaborn**

### 3. Modeling & Prediction
- Applied **Random Forest Regressor**
- Optimized hyperparameters with **GridSearchCV**
- Evaluated model performance using:
  - Mean Squared Error (MSE)
  - R² Score

---

## ⚙️ Tools & Libraries

- **Programming Language**: Python
- **Data Handling**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Modeling**: Scikit-learn (RandomForestRegressor, GridSearchCV)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AykanIpek/predict-house-price.git
   cd predict-house-price
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook or Python scripts:
   ```bash
   jupyter notebook notebooks/FinalProject.ipynb
   ```

---

## 📊 Results

- **Best Model**: Random Forest Regressor
- **Performance**: High R² score with optimized parameters
- **Outcome**: Reliable predictions of London’s average house prices

---

## 📌 Future Improvements

- Experiment with deep learning models (LSTM, XGBoost, LightGBM)
- Incorporate external economic indicators (GDP, unemployment, inflation)
- Deploy model with a simple web dashboard (Flask/Streamlit)

---

📧 **Author**: AykanIpek  
🎓 *Istanbul Technical University*
