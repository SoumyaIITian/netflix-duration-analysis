# Netflix Duration Analysis 📺

This repository contains an end-to-end statistical analysis project exploring whether TV shows tend to have longer durations than movies on Netflix. The analysis was conducted using Python in Jupyter Notebook, with a focus on data cleaning, exploratory data analysis (EDA), and statistical hypothesis testing.

---

## 🧩 Problem Statement

**Do TV shows on Netflix have longer durations than movies?**

This question is answered using descriptive statistics and an independent t-test, helping to determine if there's a significant difference in average durations.

---

## 📊 Dataset

- **Source:** [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- The dataset includes metadata on movies and TV shows available on Netflix, such as type, duration, country, release year, etc.

---

## 🔧 Tools & Libraries Used

- **Python 3**
- `pandas` – data manipulation
- `matplotlib` & `seaborn` – visualizations
- `scipy.stats` – statistical testing (t-test)
- `Jupyter Notebook` – project environment

---

## 📈 Key Steps in the Analysis

1. **Data Cleaning**  
   - Filtered movies and TV shows separately  
   - Extracted numeric values from `duration` column

2. **Exploratory Data Analysis (EDA)**  
   - Generated histograms and boxplots for visual comparison  
   - Described central tendency (mean, median) and spread (std deviation)

3. **Statistical Hypothesis Testing**  
   - Applied **independent two-sample t-test**  
   - Tested whether the mean duration of TV shows is significantly different from that of movies

---

## 📌 Results

- Visualizations and descriptive stats indicated a difference in duration distributions
- T-test provided statistical evidence supporting/rejecting the hypothesis

> 📣 The full methodology and results are available in the Jupyter Notebook.

---

## 📂 Repository Structure

├── Netflix_Duration_Analysis.ipynb # Main analysis notebook
├── README.md # Project documentation
└── netflix_titles.csv # Original dataset (optional)


---

## ✅ Next Steps

- Extend analysis to compare across genres or countries
- Normalize TV show durations (e.g., episodes × avg runtime)
- Deploy insights via dashboard (Streamlit/Gradio)

---

## 📬 Contact

**Soumyajit Mondal**  
Final Year Dual Degree Student, IIT Kharagpur  
📧 soumyamondal299@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/soumyajit-mondal)
---

