Data Science Begineers Project
# Exploratory-Data-Analysis-EDA-

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **World Happiness Report** dataset from [Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness).  
The analysis explores factors influencing happiness scores worldwide, including **GDP per capita**, **social support**, **health (life expectancy)**, **freedom**, **trust**, and **generosity**.  
The project includes **univariate, bivariate, and multivariate** analysis, along with an **automatic insights generator**.

## 📂 Dataset
- **Source**: [Kaggle - World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness)  
- **Columns Used**:
  - `Country`
  - `Region`
  - `Happiness Rank`
  - `Happiness_Score`
  - `GDP_per_Capita`
  - `Social_Support`
  - `Health`
  - `Freedom`
  - `Trust`
  - `Generosity`
  - `Dystopia Residual`
  - `Year`

## 🛠️ Installation & Requirements
**Python Version:** 3.8 or above  
**Required Libraries:**
```bash
pip install pandas numpy matplotlib seaborn
```
``` bash
pip install plotly
```

## 🚀 How to Run
1. Clone this repository:
  ```
  git clone https://github.com/your-username/world-happiness-eda.git
  cd world-happiness-eda
  ```
2. Place the dataset file (world_happiness.csv) inside the project folder.
3. Open the Jupyter Notebook:
  ```
  jupyter notebook world_happiness_eda.ipynb
  ```
4. Run the cells in order to generate graphs & insights.

## 📊 Project Structure
``` bash
world-happiness-eda/
│
├── world_happiness_eda.ipynb    # Main analysis notebook
├── world_happiness.csv          # Dataset (not included, download from Kaggle)
├── README.md                    # Project documentation
└── requirements.txt             # Python dependencies
```

## 📈 Analysis Performed
Univariate Analysis: Distribution plots, top 10 happiest countries per year

Bivariate Analysis: Correlation heatmaps, scatter plots (GDP vs Happiness, Health vs Happiness)

Multivariate Analysis: Pairplots, 3D plots, region-wise comparisons

Time Trends: Yearly changes in average happiness score

Automatic Insights Generator: Summarizes key findings from correlations & trends

## 🤝 Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

## 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

## 👩‍💻 Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)


