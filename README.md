# 🎬 Netflix Dataset Analysis | Pandas-based Python Project

A data analysis project built using **Pandas** and **NumPy**, focused on exploring and extracting insights from the popular **Netflix Titles Dataset**. This project covers real-world data cleaning, transformation, filtering, aggregation, and analytical operations — perfect for Python learners diving into data analysis.

---

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Pandas](https://img.shields.io/badge/Library-Pandas-orange) ![License](https://img.shields.io/badge/License-MIT-green)

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Features](#-features)
- [Concepts Covered](#-concepts-covered)
- [Installation](#-installation)
- [How to Use](#-how-to-use)
- [Dataset Source](#-dataset-source)
- [Insights Summary](#-insights-summary)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)
- [License](#-license)

---

## 📚 Project Overview

This project performs a step-by-step analysis of the **Netflix Titles Dataset** using Python. It explores content distribution, release trends, rating patterns, and more — all while applying foundational Pandas techniques.

🎯 **Key Objectives**:
- Load, clean, and analyze a real-world dataset
- Practice essential Pandas operations
- Derive actionable insights from messy data

---

## 🚀 Features

✅ Load and explore structured datasets  
✅ Clean missing values and inconsistent formats  
✅ Filter data based on logic and string conditions  
✅ Group data for aggregation and comparisons  
✅ Derive new columns using datetime and string ops  
✅ Answer analytical business-like questions

---

## 🧠 Concepts Covered

- DataFrame basics: `.head()`, `.tail()`, `.shape`, `.info()`
- Data cleaning: `.isnull()`, `.dropna()`, `pd.to_datetime()`
- Filtering: logical conditions, `.str.contains()`, `.str.extract()`
- Column transformations and feature engineering
- GroupBy operations and aggregations
- Exploratory data analysis and insights

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/aayantasneem/netflix-pandas-analysis.git

# Navigate to the folder
cd netflix-pandas-analysis

# Install dependencies
pip install pandas numpy

---

## 🎮 How to Use

1. Download or clone the repo.
2. Place the `netflix_titles.csv` file in the same folder.
3. Open and run the notebook/script in your preferred environment (e.g., Jupyter, VS Code).
4. Follow the analysis step by step from loading to final insights.

---

## 📂 Dataset Source

Dataset used: `netflix_titles.csv`  
Source: [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) — contains Netflix titles up to 2021 with metadata like cast, country, rating, release year, etc.

---

## 📈 Insights Summary

### 📌 Part 1: Basic Operations
- Dataset loaded and explored using `.shape`, `.columns`, `.info()`.
- Cleaned missing fields and converted date formats.

### 📌 Part 2: Filtering & Grouping
- Filtered titles by country, release year, and duration.
- Grouped data to get content counts per type, country, and year.

### 📌 Part 3: Analytical Questions
- **TV-MA** is the most frequent rating.
- **United States** has the highest content volume.
- Most content is **recent (post-2015)**.
- Average movie release year ≈ **2013.93**

---

## 🚧 Future Enhancements

- Visualize trends using Matplotlib or Seaborn  
- Add interactive filtering via Streamlit or Dash  
- Extend to recent Netflix data (scraping or APIs)  
- Perform NLP on `description` column for genre/topic analysis

---

## ✨ Author

Developed with ❤️ by **M. Aayan Tasneem**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/muhammadaayantasneem)

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
