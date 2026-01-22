# Netflix Content Strategy Analysis 🎬

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Da7vMZw4zXaIqJIGck3_3a_VqhKUtVMa?usp=sharing)
[![Kaggle](https://img.shields.io/badge/Notebook-Kaggle-blue.svg)](https://www.kaggle.com/code/vishanshm/project-netflix-content-dataset-eda)

Welcome to the second project of the **"21 Projects, 21 Days"** GFG course. Today's project moves beyond basic EDA into in-depth analysis of streaming data, focusing on time-series trends, content distribution, and global production.

## 📌 Project Objective
The goal is to analyze the Netflix dataset to uncover how the platform's content strategy has evolved. We explore:
* Trends in content production and release over time.
* The balance between Movies and TV Shows.
* Regional contributions to the Netflix library.
* Analysis of genres and content maturity ratings.

## 🛠️ Concepts & Tools Used
* **Data Cleaning:** Handling significant missing values in columns like `director`, `cast`, and `country`.
* **Time-Series Analysis:** Converting string dates into `datetime` objects to analyze monthly and yearly upload trends.
* **Text Processing:** Parsing multi-value strings in the `listed_in` (genres) column.
* **Advanced Visualization:** Using `Seaborn` and `Matplotlib` for distribution plots and `WordCloud` for genre visualization.

## 📊 Key Insights from Analysis
* **Library Composition:** Approximately **70%** of Netflix content consists of Movies, while **30%** are TV Shows.
* **Growth Trend:** There was a massive surge in content additions starting around **2015**, peaking between 2018 and 2019.
* **Content Age:** Most content on Netflix is relatively new, with a significant portion released after 2010.
* **Ratings Distribution:** The most common rating is **TV-MA**, indicating a heavy focus on mature audiences.

## 🚀 Repository Structure
```text
Project-Netflix_Content_Dataset_EDA/
├── Project-Netflix_Content_Dataset_EDA.ipynb   # Main analysis notebook
├── netflix_titles.csv                          # Dataset (if applicable)
└── README.md                                   # Project documentation
