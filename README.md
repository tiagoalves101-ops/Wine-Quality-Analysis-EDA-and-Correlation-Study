# 🍷 Wine Quality Analysis — EDA and Correlation Study

This project explores the **Wine Quality dataset** through **Exploratory Data Analysis (EDA)** to uncover the chemical characteristics that influence wine quality.

The analysis uses the dataset `winequality-red.csv` (synthetic version based on real data) and reproduces key insights through visualization and correlation analysis.

---

## 📊 Objectives
- Analyze the distribution of wine quality scores.
- Explore relationships between physicochemical features (acidity, alcohol, sulphates, pH, etc.).
- Identify variables most correlated with wine quality.
- Visualize data patterns with histograms, bar plots, scatter plots, and a correlation heatmap.

---

## 🧰 Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

## 📈 Main Visualizations
1. **Quality Distribution (Bar Plot)** – shows the frequency of each quality score.  
2. **Correlation Heatmap** – highlights positive and negative relationships among variables.  
3. **Histograms** – visualize feature distributions such as *fixed acidity* and *alcohol content*.  
4. **Scatter Plot (Alcohol vs pH)** – color-coded by wine quality to reveal chemical trends.

---

## 🔍 Key Insights
- Most wines are rated between **5 and 6**, indicating medium quality.  
- **Alcohol** has a **strong positive correlation** with quality.  
- **Volatile acidity** shows a **negative correlation** with quality.  
- pH and fixed acidity are inversely related.  

These relationships are consistent with real-world enological findings.

---

## 📂 Files
| File | Description |
|------|--------------|
| `WinequalityEDA.ipynb` | Full notebook with analysis and plots |
| `winequality-red.csv` | Dataset used in the analysis |
| `bar_plot.png` | Distribution of wine quality |
| `heatmap.png` | Correlation matrix |
| `histplot.png`, `histplot2.png` | Histograms for selected features |
| `scatterplot.png` | Alcohol vs pH colored by quality |

---

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook WinequalityEDA.ipynb
The notebook loads winequality-red.csv automatically and reproduces all plots.
