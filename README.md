# ⚽ FIFA World Cup 2026 — Player Performance Analysis

> **Task 2 | SkillCraft Technology Data Science Internship**

Exploratory Data Analysis (EDA) on the FIFA World Cup 2026 Player Performance Dataset, uncovering patterns across player stats, nationalities, positions, physical attributes, and market values.

---

## 📌 Project Overview

This project performs a comprehensive EDA on FIFA World Cup 2026 player data. The goal is to extract meaningful insights about player performance, identify trends by position and nationality, analyze physical attributes, and segment players using clustering techniques.

---

## 📁 Repository Structure

```
SCT_DS_2/
│
├── FIFA.ipynb                        # Main Jupyter Notebook (EDA)
├── FIFA_DATASET.csv                  # Raw dataset
│
├── Age_Group_Stats.csv               # Aggregated stats by age group
├── Player_Performance.csv            # Individual player performance metrics
├── National_Performance.csv          # Performance aggregated by nationality
├── Position_Stats.csv                # Stats grouped by player position
│
├── eda_univariate_distributions.png
├── eda_categorical_distributions.png
├── eda_correlation_matrix.png
├── eda_age_performance.png
├── eda_physical_attributes.png
├── eda_position_analysis.png
├── eda_nationality_rating.png
├── eda_market_value.png
├── eda_foot_distribution.png
├── eda_passing_analysis.png
├── eda_shot_analysis.png
├── eda_temporal_performance.png
└── eda_kmeans_elbow.png
```

---

## 📊 Dataset

**Source:** [FIFA World Cup 2026 Player Performance Dataset — Kaggle](https://www.kaggle.com/datasets/rauffauzanrambe/fifa-world-cup-2026-player-performance-dataset)

The dataset contains comprehensive statistics and advanced metrics for players participating in the FIFA World Cup 2026, including:

- Player demographics (age, nationality, preferred foot)
- Position and role information
- Performance metrics (goals, assists, passes, shots)
- Physical attributes (height, weight, speed)
- Market value estimates
- Tournament-level performance data

---

## 🔍 Analysis Performed

| Analysis | Description |
|---|---|
| **Univariate Distributions** | Distribution of key numerical features |
| **Categorical Distributions** | Breakdown by position, foot preference, nationality |
| **Correlation Matrix** | Heatmap of feature correlations |
| **Age vs Performance** | How performance metrics vary across age groups |
| **Physical Attributes** | Height, weight, and speed analysis |
| **Position Analysis** | Comparing stats across player positions |
| **Nationality Ratings** | Average ratings grouped by country |
| **Market Value** | Distribution and factors affecting player value |
| **Passing Analysis** | Pass accuracy, volume, and efficiency |
| **Shot Analysis** | Shot attempts, on-target rate, and conversion |
| **Temporal Performance** | Performance trends over time |
| **K-Means Clustering (Elbow)** | Player segmentation using unsupervised learning |

---

## 🛠️ Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — K-Means clustering

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Mehul5124/SCT_DS_2.git
cd SCT_DS_2
```

### 2. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Run the Notebook
```bash
jupyter notebook FIFA.ipynb
```

---

## 📈 Key Insights

- **Age & Performance:** Players in the 24–29 age bracket tend to show the highest overall performance ratings.
- **Position Trends:** Forwards lead in shots and goals, while midfielders dominate passing metrics.
- **Physical Attributes:** Taller players are more concentrated in defensive and goalkeeping positions.
- **Market Value:** Strong correlation observed between overall rating, age, and market value.
- **Nationality:** A few dominant nations consistently show higher average player ratings.
- **Preferred Foot:** Right-footed players form the majority, with left-footed players showing comparable performance.
- **Clustering:** K-Means elbow analysis identifies optimal player segments for grouping similar performer profiles.

---

## 🏆 Internship Context

This project was completed as **Task 2** of the **SkillCraft Technology Data Science Internship**, focused on performing exploratory data analysis to uncover patterns and relationships in real-world sports data.

---

## 👤 Author

**Mehul** — [@Mehul5124](https://github.com/Mehul5124)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
