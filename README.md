````markdown
# Bank Loan Default Prediction

This project performs end-to-end analysis and machine learning on a bank loan dataset in order to:
- understand customer characteristics and trends,
- calculate key performance indicators (KPIs),
- visualize business insights, and
- predict whether a loan is likely to default.

The entire analysis is done using a Python Jupyter Notebook (`Bank_Loan.ipynb`) and includes both exploratory analysis and model building (Random Forest classifier).

---

## 📌 Project Objectives

- Clean and preprocess the raw bank loan dataset  
- Perform descriptive analytics and derive KPIs  
- Visualize key metrics (loan purpose, home ownership, state distribution, etc.)
- Build a machine learning model to classify **Good** vs **Bad** loans
- Allow user to test the prediction with custom input values

---

## 🛠️  Tech Stack

| Tool / Library       | Purpose                              |
|----------------------|---------------------------------------|
| Python               | Primary programming language          |
| Pandas / NumPy       | Data cleaning and manipulation        |
| Matplotlib / Seaborn | Exploratory data visualization        |
| Scikit-Learn         | Feature preprocessing & ML model      |
| Jupyter Notebook     | Development and presentation          |

---

## 🔎  Workflow Summary

| Step | Description |
|------|------------|
| 1 | Load the CSV data and inspect the structure |
| 2 | Handle missing values and duplicates |
| 3 | Convert dates and numeric columns to correct datatype |
| 4 | Calculate basic KPIs (MTD Applications, Avg Interest Rate, Good vs Bad loan amount etc.) |
| 5 | Create visualizations (monthly trend, loan term distribution, home ownership treemap, etc.) |
| 6 | One-hot encode categorical variables |
| 7 | Train/Test split |
| 8 | Build and evaluate a **RandomForestClassifier** |
| 9 | Allow user to enter new applicant info for prediction |

---

## 📈  Visualization Highlights

- **Monthly Loan Applications Trend** (line chart)
- **Top States by Loan Count**
- **Loan Term Distribution** (donut chart)
- **Employee Length vs Loan Applications**
- **Loan Purpose Breakdown**
- **Home Ownership Distribution** (treemap)

---

## 🔧  How to Run

### ✅ Prerequisites
- Python 3.8+
- Jupyter Notebook

### ✅ Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
````

### ✅ Run Notebook

```bash
jupyter notebook Bank_Loan.ipynb
```
---

## ✅  Model Output

* **Accuracy** : displayed after model evaluation
* **Classification Report** : Precision, Recall, F1-Score
* **Confusion Matrix** : for Good vs Bad loan prediction

---

## 🚀  Final Remark

This project not only explores historical loan data but turns it into a usable **prediction system**.
It’s useful for practice in both **EDA** and **applied machine learning** in a **real-world banking scenario**.

---

*Made with ❤️ by Abhay — Data Analyst*

```
