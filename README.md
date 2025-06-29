# 🏅 Olympics Data Analysis (1976–2008)

This project explores historical data from the Summer Olympics between 1976 and 2008 to uncover insights about medal trends, top-performing countries and athletes, and gender participation. It also includes a basic machine learning model to predict medal outcomes.

---

## 📌 Project Objectives

1. **Data Preparation**
   - Load and clean the dataset
   - Handle missing values
   - Convert data to usable formats

2. **Exploratory Data Analysis (EDA)**
   - Analyze medal trends across years
   - Identify top athletes and countries
   - Explore gender distribution

3. **Visualizing Key Insights**
   - Medals by year, country, and sport
   - Gender distribution in top sports
   - Heatmaps and comparative charts

4. **Predictive Analysis**
   - Train a logistic regression model
   - Predict medal-winning likelihood based on athlete attributes
   - Evaluate model performance

---

## 🧰 Tech Stack

- **Python 3**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Machine learning
- **Jupyter Notebook / Google Colab** – Development environment

---

## 📁 Dataset

- File: `Summer-Olympic-medals-1976-to-2008.csv`
- Contains records of medal-winning athletes from 1976 to 2008 including:
  - Year, City, Sport, Discipline, Event, Athlete
  - Gender, Country, Medal type

---

## 📊 Visuals & Analysis Highlights

- 📈 Medals over time (line plots)
- 🌍 Top 10 countries by medal count
- 🧍 Top 10 athletes
- 🎯 Heatmap of medals by country & year
- ♀️♂️ Gender distribution in sports
- 🤖 Logistic regression to predict medal chances

---

## 🤖 Predictive Modeling

- Features used:
  - `Country`, `Sport`, `Gender`
- Model:
  - `LogisticRegression` from scikit-learn
- Evaluation:
  - Accuracy score, confusion matrix, classification report
- Note:
  - Simulated "non-winners" added due to dataset containing only medalists

---

## 🚀 How to Run

1. Clone this repository:
   ```bash

   

   git clone https://github.com/your-username/olympics-data-analysis.git
   cd olympics-data-analysis
```
2. Open the notebook in Jupyter or Google Colab:

File: Olympics_Data_Analysis.ipynb

3. Run all cells:

Make sure Summer-Olympic-medals-1976-to-2008.csv is in the same directory
```
✅ Deliverables 
```
📒 Cleaned & structured Jupyter Notebook

📊 Visualizations & Insights

🤖 Logistic regression model

📂 Dataset used

📘 This README

