 <div align="center">

# 🚗 Used Car Price Analysis

**An exploratory data analysis project to understand used car prices using Python, Pandas, NumPy, Matplotlib, and Seaborn.**

[![Language](https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=for-the-badge&logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/Library-NumPy-013243?style=for-the-badge&logo=numpy)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-11557C?style=for-the-badge)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-76B900?style=for-the-badge)](https://seaborn.pydata.org/)
[![Status](https://img.shields.io/badge/Status-In%20Progress-orange?style=for-the-badge)](#-project-status)

[Overview](#-overview) •
[Objectives](#-project-objectives) •
[Dataset](#-dataset) •
[Workflow](#-technical-workflow) •
[Technologies](#-technologies-used) •
[Installation](#-installation--usage) •
[Learning Outcomes](#-learning-outcomes) •
[Project Status](#-project-status)

---

</div>

## 📌 Overview

**Used Car Price Analysis** is a Python-based data analysis project focused on exploring a used car dataset and understanding the factors associated with car selling prices.

The project uses data analysis and visualization libraries to inspect the dataset, identify data quality issues, calculate statistical summaries, and explore relationships between vehicle characteristics and selling prices.

The main goal is to develop practical skills in data cleaning, exploratory data analysis (EDA), statistical interpretation, and data visualization.

---

## 🎯 Project Objectives

- Understand the structure and characteristics of a real-world dataset.
- Identify and handle duplicate records.
- Check for missing values and investigate data quality.
- Calculate descriptive statistics for numerical columns.
- Explore how vehicle age and kilometers driven relate to selling price.
- Compare selling prices across fuel types, seller types, transmission types, and ownership categories.
- Create visualizations to communicate useful findings.
- Practice writing clear, reproducible data analysis code.

---

## 📊 Dataset

The project uses a used car dataset containing information about vehicles and their selling prices.

### Dataset Features

| Column | Description |
| :--- | :--- |
| `name` | Name or model of the car |
| `year` | Year the car was manufactured |
| `selling_price` | Selling price of the car |
| `km_driven` | Total kilometers driven |
| `fuel` | Fuel type |
| `seller_type` | Type of seller |
| `transmission` | Transmission type |
| `owner` | Previous ownership category |

**Dataset file:** `data/car_data.csv`

The dataset is included in this repository so the analysis can be reproduced locally.

---

## 🏗️ Technical Workflow

The project follows a structured data analysis workflow:

### 1. Data Loading and Inspection

- Load the CSV file using Pandas.
- Inspect the first and last records.
- Examine dataset dimensions and column names.
- Review data types and summary information.

### 2. Data Cleaning

- Check for missing values.
- Identify duplicate records.
- Remove duplicate rows where appropriate.
- Verify the dataset after cleaning.

### 3. Exploratory Data Analysis (EDA)

- Calculate mean, median, minimum, maximum, and other descriptive statistics.
- Examine the distribution of selling prices.
- Investigate the relationship between kilometers driven and selling price.
- Compare prices across manufacturing years.
- Analyze categorical features such as fuel type, seller type, and transmission.

### 4. Data Visualization

Use Matplotlib and Seaborn to create charts that help reveal patterns and differences in the dataset.

Planned visualizations include:

- Selling price distribution.
- Selling price versus kilometers driven.
- Manufacturing year versus selling price.
- Selling price comparisons across fuel and transmission types.
- Comparisons of prices across ownership categories.

### 5. Interpretation and Findings

- Interpret the patterns observed in the charts.
- Distinguish correlations and associations from causal relationships.
- Consider dataset limitations, including small groups and possible outliers.
- Summarize the findings in clear, understandable language.

---

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **Python** | Main programming language |
| **Pandas** | Data loading, cleaning, manipulation, and analysis |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical charts and visual exploration |
| **Jupyter Notebook** | Interactive analysis and documentation |
| **Git & GitHub** | Version control and project hosting |

---

## 🚀 Installation & Usage

### 1. Prerequisites

Ensure you have the following installed:

- Python 3.12 or a compatible Python version.
- Git.
- Visual Studio Code or Jupyter Notebook.

### 2. Clone the Repository

```bash
git clone https://github.com/husnianmahmood/used_car_price_analysis_project_py.git
```

### 3. Navigate to the Project Directory

```bash
cd used_car_price_analysis_project_py
```

### 4. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 6. Open the Notebook

Launch Jupyter Notebook:

```bash
python -m jupyter notebook
```

Alternatively, open `used_car_price_analysis.ipynb` in Visual Studio Code and select the project's virtual environment as the Python kernel.

Run the notebook cells in order to reproduce the analysis.

---

## 📁 Project Structure

```text
used_car_price_analysis_project_py/
│
├── data/
│   └── car_data.csv
│
├── images/
│   └── (visualizations, when added)
│
├── used_car_price_analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🧠 Learning Outcomes

Working on this project helps develop practical data analysis skills:

- **Data Inspection:** Understanding dataset dimensions, columns, data types, and distributions.
- **Data Cleaning:** Identifying duplicate records and validating data quality.
- **Statistical Analysis:** Using descriptive statistics to summarize numerical data.
- **Exploratory Data Analysis:** Investigating patterns and relationships between variables.
- **Data Visualization:** Presenting findings with Matplotlib and Seaborn.
- **Analytical Thinking:** Interpreting patterns carefully and avoiding unsupported conclusions.
- **Reproducible Workflows:** Organizing code and dependencies so the analysis can be repeated.
- **Version Control:** Maintaining a project on GitHub with Git.

---

## ⚠️ Project Limitations

- The analysis describes patterns in the available dataset; it does not establish that a particular feature causes a change in selling price.
- Some categories may contain too few records for reliable comparisons.
- The dataset may not represent the entire used car market.
- The project focuses on exploratory data analysis and does not currently include a machine learning price prediction model.

---

## 📌 Project Status

**In Progress**

The project is being developed as part of my practical learning journey in Python and data analysis. The focus is on building a solid foundation in data cleaning, exploratory analysis, visualization, and interpretation before moving to more advanced techniques.

---

## 👨‍💻 Author

**Husnain Mahmood**

Software Engineering Student | Python & C++ Learner | Aspiring AI Engineer

- GitHub: [@husnianmahmood](https://github.com/husnianmahmood)

---

<div align="center">

**Built with Python and a commitment to continuous learning.**

</div>
