# 🌍 Global Happiness Report Analysis

> **Exploring what makes countries happier — through data, statistics, and visualization.**

---

## 📌 About the Project

**Global Happiness Report Analysis** is a data analysis project based on the **World Happiness Report** dataset.

The goal of this project is to explore happiness levels across countries and understand how different social, economic, health, and lifestyle-related factors are associated with the Happiness Score.

The project uses Python-based data analysis and visualization techniques to discover patterns and relationships within the dataset.

---

## 🎯 Project Objectives

This project aims to:

- 🌎 Analyze happiness levels across different countries
- 🏆 Identify the **Top 10 Happiest Countries**
- 📉 Identify the **Bottom 10 Least Happy Countries**
- 💰 Explore the relationship between **GDP per capita** and Happiness Score
- 🤝 Analyze the relationship between **Social Support** and Happiness Score
- ❤️ Study **Healthy Life Expectancy** and Happiness Score
- 🕊️ Analyze **Freedom to Make Life Choices** and Happiness Score
- 🎁 Explore **Generosity** and Happiness Score
- 🏛️ Analyze **Perceptions of Corruption** and Happiness Score
- 📊 Perform correlation analysis between important variables
- 🔥 Visualize relationships using charts and a correlation heatmap

---

## 📊 Dataset

The dataset contains information about **156 countries** and **9 variables** related to happiness.

### Dataset Features

| Column | Description |
|---|---|
| `Overall rank` | Ranking of the country based on Happiness Score |
| `Country or region` | Name of the country or region |
| `Score` | Overall Happiness Score |
| `GDP per capita` | Contribution of economic performance to happiness |
| `Social support` | Level of social support |
| `Healthy life expectancy` | Healthy life expectancy indicator |
| `Freedom to make life choices` | Freedom to make personal life choices |
| `Generosity` | Generosity indicator |
| `Perceptions of corruption` | Perception of corruption |

---

## 🔍 Analysis Performed

### 1. Dataset Exploration
- Dataset dimensions
- Column names
- Data types
- Statistical summary

### 2. Data Quality Check
- Missing value analysis
- Duplicate row detection

### 3. Happiness Ranking
- Top 10 happiest countries
- Bottom 10 least happy countries

### 4. Relationship Analysis
The project analyzes Happiness Score against:

- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption

### 5. Correlation Analysis
Correlation coefficients are calculated to identify the strength and direction of relationships between Happiness Score and other numerical variables.

### 6. Data Visualization
Multiple charts are created to make the findings easier to understand, including scatter plots, bar charts, and a correlation heatmap.

---

## 📈 Key Visualizations

The notebook includes:

- 🏆 Top 10 Happiest Countries
- 📉 Bottom 10 Least Happy Countries
- 💰 GDP vs Happiness Score
- 🤝 Social Support vs Happiness Score
- ❤️ Healthy Life Expectancy vs Happiness Score
- 🕊️ Freedom vs Happiness Score
- 🎁 Generosity vs Happiness Score
- 🏛️ Perceptions of Corruption vs Happiness Score
- 🔥 Correlation Heatmap
- 📊 Happiness Factor Correlation Ranking

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Data analysis |
| 🐼 Pandas | Data manipulation |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| ☁️ Google Colab | Development environment |
| 🐙 GitHub | Project hosting |

---

## 📂 Project Structure

```text
Global-Happiness-Analysis/
│
├── happiness_analysis.ipynb
├── World_Happiness_Report.csv
├── README.md

```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd Global-Happiness-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

Open:

```text
happiness_analysis.ipynb
```

You can run it using **Google Colab** or **Jupyter Notebook**.

### ⚠️ Dataset Path

Make sure the CSV file is located in the same folder as the notebook:

```text
World_Happiness_Report.csv
```

The notebook reads the dataset using:

```python
df = pd.read_csv("World_Happiness_Report.csv")
```

---

## 📌 Important Note

This project focuses on **correlation and exploratory analysis**.

A correlation between two variables does **not** prove that one variable directly causes the other. The results should therefore be interpreted as relationships or associations within the dataset.

---

## 💡 Conclusion

The project provides an exploratory view of global happiness and examines how Happiness Score is associated with economic, social, health, freedom, generosity, and corruption-related indicators.

Through rankings, visualizations, and correlation analysis, the project highlights important patterns in happiness levels across countries.

---

## 👨‍💻 Author

**krisha kukadiya**

### 🌍 Global Happiness Report Analysis
**Data Analysis • Visualization • Python**
