# ⚽ Football Players EDA (2025–26 Season)

A comprehensive **Exploratory Data Analysis (EDA)** of football player statistics from the 2025–26 season across Europe’s top five leagues.  
This project focuses on uncovering performance trends, positional differences, and feature relationships through structured analysis and visualization.

---

## 📌 Project Overview

Modern football generates massive amounts of performance data.  
This notebook explores how player age, position, nationality, and match involvement relate to real-world outcomes such as goals, assists, and defensive contributions.

The goal is to provide a **data-driven perspective** on professional football performance using Python-based analysis.

---

## 🎯 Objectives

- Understand player demographics (age, nationality, position)
- Analyze goal-scoring patterns and performance trends
- Compare positional contributions
- Explore relationships between numerical features using correlation analysis
- Identify role-specific performance clusters (attackers vs goalkeepers)

---

## 🧠 Key Insights

### 📊 Dataset Composition
- Midfielders represent the largest positional group  
- Defenders and forwards follow  
- Goalkeepers form the smallest category, explaining structural missing values in GK-specific columns  

---

### ⏳ Age Patterns
- Most players fall between **20–28 years**, indicating peak professional age  
- Goalkeepers tend to have slightly higher median age compared to outfield players  

---

### ⚡ Performance Trends
- Forwards score significantly more goals on average than other positions  
- Goal distribution is highly right-skewed, showing that only a small fraction of players score heavily  

---

### 🌍 Nationality Insights
- A small number of countries dominate player representation  
- Average goal contribution varies across top nationalities  

---

### 🔗 Feature Relationships
- Goals show positive correlation with attacking metrics  
- Goalkeeping statistics form a separate correlated cluster, highlighting role-specific performance  

---

## ✅ Overall Conclusion

The dataset strongly reflects real-world football dynamics:

- Age, position, and attacking involvement play major roles in performance  
- Clear separation exists between attacking and goalkeeping metrics  
- A limited group of elite players contributes disproportionately to total goals  

This EDA provides a structured analytical foundation for understanding modern football player performance.

---

## 📂 Dataset Information

Player statistics from the **2025–2026 season** across Europe’s top five leagues.

Two CSV files are included:

- `players_data-2025_2026.csv`  
  → Full dataset with 250+ columns covering attacking, passing, defending, and goalkeeping metrics.

- `players_data_light-2025_2026.csv`  
  → Lightweight version containing the most essential performance features.

The dataset is automatically updated weekly and sourced from :contentReference[oaicite:0]{index=0}.

---

## 📊 Feature Groups

### Basic Player Information
- Player name, nationality, position, club, league  
- Age, birth year  

### Playing Time
- Matches played, starts, minutes, full 90s  

### Attacking Metrics
- Goals, assists, G+A  
- Expected goals (xG), expected assists (xAG)  
- Non-penalty goals  

### Defensive Metrics
- Tackles, interceptions, blocks  
- Clearances, errors leading to goals  

### Passing & Creativity
- Progressive passes  
- Key passes  
- Pass completion %  
- Expected assists  

### Goalkeeping (GK only)
- Goals against  
- Saves  
- Save percentage  
- Clean sheets  

### Possession & Control
- Touches  
- Carries  
- Progressive runs  
- Miscontrols  

### Discipline & Miscellaneous
- Yellow / red cards  
- Penalties won / conceded  
- Ball recoveries  

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🔗 Kaggle Notebook

View the complete interactive notebook on Kaggle:

👉 https://www.kaggle.com/code/netramfaran/eda-of-football-players-2025-26

