# 📊 Sales Prediction Using Python

A machine learning project that predicts future sales based on advertising spend across TV, Radio, and Newspaper platforms. Built as part of the **CodeAlpha Data Science Internship**.

---

## 📁 Project Structure
---

## 📌 Problem Statement

Businesses invest heavily in advertising but often lack clarity on which platform drives the most sales. This project builds a predictive model to forecast sales based on advertising budgets and identifies which channels deliver the highest ROI.

---

## 📂 Dataset

| Property | Details |
|---|---|
| File | Advertising.csv |
| Rows | 200 |
| Features | TV, Radio, Newspaper |
| Target | Sales |
| Units | Spend in $thousands / Sales in k units |

---

## ⚙️ Workflow

1. **Data Loading** — Load CSV, inspect shape and dtypes
2. **EDA** — Null check, statistics, correlation heatmap, pairplot, sales distribution
3. **Feature Engineering** — Added `TV_Radio` interaction feature (TV × Radio)
4. **Train-Test Split** — 80% train, 20% test
5. **Model Training** — Linear Regression & Random Forest Regressor
6. **Evaluation** — MAE, RMSE, R² Score
7. **Visualization** — Actual vs Predicted plots, Feature Importance chart
8. **Business Insights** — Ad channel impact analysis

---

## 🤖 Models Used

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression | ~0.90 | ~1.20 | ~0.90 |
| Random Forest | ~0.35 | ~0.55 | ~0.97 |

> Random Forest significantly outperforms Linear Regression on this dataset.

---

## 📊 Visualizations

- Correlation Heatmap
- Pairplot (TV, Radio, Newspaper vs Sales)
- Sales Distribution Plot
- Actual vs Predicted — Linear Regression
- Actual vs Predicted — Random Forest
- Feature Importance Bar Chart

---

## 💡 Key Insights

- **TV** advertising has the strongest positive impact on sales
- **Radio** has a moderate effect and works well combined with TV
- **Newspaper** contributes the least and has the lowest ROI
- **TV × Radio** interaction feature improves model accuracy
- **Recommendation:** Allocate higher budget to TV and Radio campaigns for maximum sales return

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Plotting |
| Seaborn | Statistical visualization |
| Scikit-learn | ML models & evaluation |

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/CodeAlpha_SalesPrediction.git
cd CodeAlpha_SalesPrediction
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Place `Advertising.csv` in the project folder

4. Open and run the notebook
```bash
jupyter notebook sales_prediction.ipynb
```

---

## 📦 Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
---

## 👩‍💻 Author

**Anjali**
B.Tech — AI & Machine Learning | NIMS University, Jaipur


