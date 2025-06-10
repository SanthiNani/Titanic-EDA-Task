# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📖 Project Description

This project involves performing an Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The objective is to extract meaningful insights and patterns from the data by employing statistical and visual techniques. The Titanic dataset provides information on the passengers aboard the ill-fated maiden voyage of the RMS Titanic, including demographics, class, fare, and survival status.

---

## 📂 Repository Structure

```

titanic-eda-task/
├── data/
│   └── Titanic.csv              # Titanic dataset used in the analysis
├── titanic\_eda.ipynb           # Jupyter Notebook performing EDA
├── report.pdf                  # PDF summary of EDA findings
└── README.md                   # Project overview and documentation

```

---

## 🔧 Tools and Libraries Used

- **Python 3.x**
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Advanced data visualization
- **Jupyter Notebook** – Interactive analysis and reporting

---

## 📊 EDA Workflow Summary

### 1. **Loading the Data**
- Read `Titanic.csv` using Pandas
- Display first few rows and column information

### 2. **Data Cleaning**
- Handled missing values in `Age` and `Embarked`
- Dropped the `Cabin` column due to high percentage of missing values
- Verified null values are handled

### 3. **Univariate Analysis**
- Plotted distributions for:
  - `Age`, `Fare` (numerical)
  - `Sex`, `Pclass`, `Survived` (categorical)
- Observed skewness in `Fare` and `Age`

### 4. **Bivariate Analysis**
- Analyzed relationships between:
  - `Survived` vs `Sex`
  - `Survived` vs `Pclass`
  - `Fare` vs `Age` vs `Survived`

### 5. **Multivariate Analysis**
- Used pairplots and scatter plots to find deeper trends
- Created a correlation heatmap of numeric features

---

## 📌 Key Insights

- **Gender**: Females had a significantly higher survival rate than males.
- **Class**: 1st class passengers had the highest survival rate.
- **Age**: Children and young adults had slightly higher survival chances.
- **Fare**: Higher fare is positively correlated with survival and class.
- **Embarked**: Majority of passengers embarked from port 'S'.

---

## 📄 Deliverables

- ✅ `Titanic.csv` – The dataset
- ✅ `titanic_eda.ipynb` – Complete analysis in notebook form
- ✅ `report.pdf` – A polished PDF summarizing all findings with visuals
- ✅ `README.md` – Documentation for GitHub

---

## 🚀 How to Run This Project

1. Clone the repository or download the ZIP.
2. Open `titanic_eda.ipynb` using Jupyter Notebook or Google Colab.
3. Run all cells to regenerate visualizations.
4. Optionally export the notebook as a PDF using `File > Download as > PDF`.

---

## 🔗 Dataset Source

[Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)

---

## 👨‍💻 Author

**Santhi Raju Peddapati**  
B.Tech in Computer Science - AI & ML  
Andhra Loyola Institute of Engineering & Technology  
Email: santhinani364@gmail.com
