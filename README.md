# 🌍 Global-Countries-Data-Analysis

![Python](https://img.shields.io/badge/Python-3.14-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)


A beginner-level **Pandas** project that explores a rich dataset of 194 countries — covering population, economy, health, energy, environment, and political data — to answer real-world analytical questions using Python.

This project was built as a hands-on practice project by an aspiring **Data Analyst**, focusing on data exploration, filtering, and aggregation using `pandas` and `numpy`.

---

## 📌 About the Project

The dataset (`Countries.csv`) contains **64 columns** and **194 rows**, with information such as:

- Country name, capital, region, continent, currency
- Population (total, male, female, urban, rural)
- GDP, inflation, tax revenue, unemployment
- Health expenditure, life expectancy, birth/death rate
- Energy production (coal, hydro, nuclear, renewable, etc.)
- CO2 / methane / greenhouse gas emissions
- Democracy score, democracy type, political leader

Using this data, the notebook (`Countries_Questions.ipynb`) explores the dataset with `.info()` and `.describe()`, then answers **10 analytical questions** using pandas operations like filtering, `nlargest`, `value_counts`, `.apply()`, and boolean indexing — with brief comments explaining the logic behind every answer.

---

## ❓ Questions Answered

1. What is the capital of the country with the highest population?
2. Which country has the least population?
3. What is the capital of the least populated country?
4. Top 5 countries with the highest democratic score.
5. How many total regions are there?
6. How many countries lie in the Eastern Europe region?
7. Who is the political leader of the second highest populated country?
8. How many countries have an unknown political leader?
9. How many countries have "Republic" in their full name?
10. Which country in the African region has the highest population?

---

## 🛠️ Tools & Libraries Used

- **Python 3**
- **Pandas** — data loading, filtering, and analysis
- **NumPy** — numerical operations
- **Jupyter Notebook** — interactive analysis environment

---

## 📂 Folder Structure

```
Global-Countries-Data-Analysis/
│
├── data/
│   └── Countries.csv              # Raw dataset
│
├── notebook/
│   └── Countries_Questions.ipynb  # Main analysis notebook (Q&A format)
│
├── README.md                      # Project documentation
└── requirements.txt                # Python dependencies
```

> 💡 Tip: Keep raw data inside a `data/` folder and notebooks inside a `notebook/` folder — this is a common convention that keeps GitHub repos clean and professional.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/waleed4we/Global-Countries-Data-Analysis.git
   cd Global-Countries-Data-Analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook notebook/Countries_Questions.ipynb
   ```

---

## 📈 Future Improvements

- [ ] Add visualizations using `matplotlib` / `seaborn` (bar charts, pie charts, scatter plots)
- [ ] Add `groupby()`-based questions (e.g., average GDP per region, average life expectancy per continent)
- [ ] Add correlation analysis (e.g., GDP vs life expectancy)
- [ ] Add a summary/insights section at the end of the notebook

---

## 🙋‍♂️ Author

**Malik Waleed Hussain**
BS Computer Science

[![GitHub](https://img.shields.io/badge/GitHub-waleed4we-181717?logo=github&logoColor=white)](https://github.com/waleed4we)

Made with 💻 and ☕ as part of my journey to becoming a Data Analyst.
Feel free to connect, give feedback, or suggest improvements!

---

## ⭐ Show Your Support

If you found this project helpful or interesting, consider giving it a ⭐ on GitHub!
