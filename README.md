<div align="center">

# Global Countries Data Analysis

**Exploring 194 countries across population, economy, health, energy, and politics — with pandas.**

<br/>

![Python](https://img.shields.io/badge/Python-3.14-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)


</div>

## Overview

A beginner-friendly **pandas** project that digs into a dataset of 194 countries to answer real-world analytical questions — no visualizations, no fluff, just clean data exploration and aggregation using Python.

Built as hands-on practice on the road to becoming a **Data Analyst**, this project focuses on filtering, grouping, and summarizing data the way you'd do it in an actual analytics workflow.

## Dataset

`Countries.csv` — **194 rows × 64 columns**, covering:

| Category | Examples |
|---|---|
| 🌐 Identity | Country, capital, region, continent, currency |
| 👥 Population | Total, male, female, urban, rural |
| 💰 Economy | GDP, inflation, tax revenue, unemployment |
| 🏥 Health | Expenditure, life expectancy, birth/death rate |
| ⚡ Energy | Coal, hydro, nuclear, renewables |
| 🌱 Environment | CO₂, methane, greenhouse gas emissions |
| 🏛️ Politics | Democracy score, democracy type, political leader |

## Questions Answered

The notebook opens with `.info()` and `.describe()` to get oriented, then works through 10 questions using `nlargest`, `value_counts`, `.apply()`, and boolean indexing:

1. Capital of the most populous country
2. Least populated country
3. Capital of the least populated country
4. Top 5 countries by democracy score
5. Total number of regions
6. Countries in Eastern Europe
7. Political leader of the 2nd most populous country
8. Countries with an unknown political leader
9. Countries with "Republic" in their full name
10. Most populous country in Africa

Each answer includes a short comment explaining the logic behind it.

## Tech Stack

- **Python 3** — core language
- **Pandas** — loading, filtering, and analysis
- **NumPy** — numerical operations
- **Jupyter Notebook** — interactive environment

## Project Structure

```
Global-Countries-Data-Analysis/
├── data/
│   └── Countries.csv              # Raw dataset
├── notebook/
│   └── Countries_Questions.ipynb  # Main analysis notebook (Q&A format)
├── requirements.txt                # Python dependencies
└── README.md
```

## Getting Started

```bash
# Clone the repo
git clone https://github.com/waleed4we/Global-Countries-Data-Analysis.git
cd Global-Countries-Data-Analysis

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebook/Countries_Questions.ipynb
```

## Roadmap

- [ ] Visualizations with `matplotlib` / `seaborn`
- [ ] `groupby()` questions — avg. GDP per region, avg. life expectancy per continent
- [ ] Correlation analysis (e.g., GDP vs. life expectancy)
- [ ] Summary & insights section

## Author

**Malik Waleed Hussain**
BS Computer Science

[![GitHub](https://img.shields.io/badge/GitHub-waleed4we-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/waleed4we)

<sub>Built with pandas, curiosity, and a lot of coffee ☕ — part of my journey to becoming a Data Analyst.</sub>

---

<div align="center">

If this project helped you, consider giving it a ⭐ — it goes a long way!

</div>
