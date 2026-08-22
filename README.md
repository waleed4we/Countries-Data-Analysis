<div align="center">

<h1>🌍 Global Countries Data Analysis</h1>

<p><em>Exploring 194 countries across population, economy, health, energy, and politics — with pandas.</em></p>

<br/>

<img src="https://img.shields.io/badge/Python-3.14-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>

</div>

<br/>

## 📌 Overview

A beginner-level **pandas** project that digs into a dataset of 194 countries to answer real-world analytical questions — clean data exploration and aggregation, the way an actual analyst would approach it.

Built as hands-on practice on the road to becoming a **Data Analyst**, this project focuses on filtering, grouping, and summarizing data rather than just displaying it.

<br/>

## 🗂️ Dataset

`Countries.csv` — **194 rows × 64 columns**

<div align="center">

| Category | Fields |
|:--|:--|
| 🌐 **Identity** | Country, capital, region, continent, currency |
| 👥 **Population** | Total, male, female, urban, rural |
| 💰 **Economy** | GDP, inflation, tax revenue, unemployment |
| 🏥 **Health** | Expenditure, life expectancy, birth/death rate |
| ⚡ **Energy** | Coal, hydro, nuclear, renewables |
| 🌱 **Environment** | CO₂, methane, greenhouse gas emissions |
| 🏛️ **Politics** | Democracy score, democracy type, political leader |

</div>

<br/>

## ❓ Questions Answered

The notebook opens with `.info()` and `.describe()` to get oriented, then works through 10 questions using `nlargest`, `value_counts`, `.apply()`, and boolean indexing — each with a short comment explaining the logic.

<table>
<tr><td>01</td><td>Capital of the most populous country</td></tr>
<tr><td>02</td><td>Least populated country</td></tr>
<tr><td>03</td><td>Capital of the least populated country</td></tr>
<tr><td>04</td><td>Top 5 countries by democracy score</td></tr>
<tr><td>05</td><td>Total number of regions</td></tr>
<tr><td>06</td><td>Countries in Eastern Europe</td></tr>
<tr><td>07</td><td>Political leader of the 2nd most populous country</td></tr>
<tr><td>08</td><td>Countries with an unknown political leader</td></tr>
<tr><td>09</td><td>Countries with "Republic" in their full name</td></tr>
<tr><td>10</td><td>Most populous country in Africa</td></tr>
</table>

<br/>

## 🛠️ Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/-Python-05122A?style=flat-square&logo=python" alt="Python"/>
<img src="https://img.shields.io/badge/-Pandas-05122A?style=flat-square&logo=pandas" alt="Pandas"/>
<img src="https://img.shields.io/badge/-NumPy-05122A?style=flat-square&logo=numpy" alt="NumPy"/>
<img src="https://img.shields.io/badge/-Jupyter-05122A?style=flat-square&logo=jupyter" alt="Jupyter"/>

</div>

<br/>

## 📂 Project Structure

```
Global-Countries-Data-Analysis/
├── data/
│   └── Countries.csv              # Raw dataset
├── notebook/
│   └── Countries_Questions.ipynb  # Main analysis notebook (Q&A format)
├── requirements.txt                # Python dependencies
└── README.md
```

<br/>

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/waleed4we/Global-Countries-Data-Analysis.git
cd Global-Countries-Data-Analysis

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebook/Countries_Questions.ipynb
```

<br/>

## 🧭 Roadmap

- [ ] Visualizations with `matplotlib` / `seaborn`
- [ ] `groupby()` questions — avg. GDP per region, avg. life expectancy per continent
- [ ] Correlation analysis (e.g. GDP vs. life expectancy)
- [ ] Summary & insights section

<br/>

<div align="center">

## 🙋‍♂️ Author

**Malik Waleed Hussain**
BS Computer Science

<a href="https://github.com/waleed4we">
<img src="https://img.shields.io/badge/GitHub-waleed4we-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<sub>Built with pandas, curiosity, and a lot of coffee ☕</sub>

<br/><br/>

⭐ **If this project helped you, consider giving it a star!** ⭐

</div>
