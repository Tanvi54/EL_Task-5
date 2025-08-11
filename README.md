# Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover patterns and trends that influenced passenger survival.  
The analysis is implemented in **Google Colab** and contains:
- Data cleaning and preprocessing
- Visualizations for understanding relationships between features
- Observations for each plot
- A final summary of findings

---

## 📂 Files in This Repository
- **Task_5.ipynb** – Google Colab notebook containing:
  - Data preprocessing (handling missing values, encoding)
  - Statistical exploration (`.describe()`, `.info()`, `.value_counts()`)
  - Visualizations (`sns.pairplot`, `sns.heatmap`, histograms, boxplots, scatterplots)
  - Observations for each visualization
  - Summary of key findings

---

## 📊 Key Highlights
- **Data Cleaning**: Handled missing values for `Age` and `Embarked`, dropped `Cabin` due to high missing rate.
- **Encoding**: Converted categorical variables (`Sex`, `Embarked`) into numerical form.
- **Visualization**:
  - Survival distribution plots
  - Feature relationships with survival
  - Correlation heatmap
- **Insights**:
  - Non-survivors outnumber survivors.
  - Survival rate varies significantly with passenger class and gender.
  - Younger passengers and females had higher survival rates.

---

## ▶️ How to Use
1. Open the `.ipynb` file in **Google Colab** or Jupyter Notebook.
2. Run all cells to see the plots and observations.
3. Review the summary at the end of the notebook for overall insights.

---

## 📌 Dataset
The dataset used is from the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data).

---

## 📝 Summary
The `.ipynb` notebook contains **plots + observations + a summary**, providing a complete overview of the Titanic survival patterns.
