# ♟️ Chess Openings Analysis Project

## 📌 Overview
This project analyzes **3.5M chess games** from an openings dataset.  
The goal is to explore:
- How openings perform across skill levels (Beginner vs Expert).
- Which openings are most popular and effective.
- How colour advantage (White vs Black) impacts win/loss percentages.
- Performance trends across opening variations.

The final output is an **interactive Power BI dashboard** for visual storytelling.

---

## 🛠️ Tech Stack
- **Python (Pandas, NumPy)** → Data cleaning & preprocessing  
- **Power BI** → Dashboard & data visualization  
- **CSV Dataset** → Chess games with openings, performance ratings, and outcomes  

---

## 📂 Dataset
Columns used:
- `Opening` → Full opening name (with variation)  
- `Colour` → White / Black  
- `Num Games` → Count of games played  
- `Perf Rating` → Performance rating of players using the opening  
- `Player Win %` → Percentage of wins  
- `Draw %` → Percentage of draws  
- `Opponent Win %` → Percentage of losses  

---

## 🔎 Data Processing (Python)

### 1. Build Base Table
- Selected relevant columns.  
- Renamed for consistency (`Perc Won`, `Perc Draw`, `Perc Lost`).  
- Split `Opening` into **Main Opening** and **Variation**.  
- Added `Opening_ID`.  

### 2. Outlier Detection
- Used **IQR method** on `Perf Rating` to detect rating outliers.  

### 3. Level Assignment
- **Beginner** → Outlier ratings  
- **Expert** → Non-outlier ratings  

---

## 📊 Dashboard Highlights

1. **Total Games** → 3.5M  
2. **Most Popular Openings** → Sicilian Defense, English Opening, French Defense, etc.  
3. **Effective Variations** → Top-performing variations (e.g., Classical Variation, Janowski Variation).  
4. **Win/Loss by Colour** → Clear advantage trends for White vs Black.  
5. **Expert vs Beginner Performance** → Breakdown of win percentages by opening.  
6. **Average Performance Gauge** → Shows overall performance rating range.  

![Dashboard Preview](Capture.PNG)

---

## 🚀 Insights
- **Popularity ≠ Effectiveness** → The Sicilian Defense is most played but not always most effective.  
- **Skill Matters** → Some openings work better for experts (e.g., Latvian Gambit), while others are safer for beginners.  
- **Colour Advantage** → White maintains a consistent win edge.  
- **Variation Depth** → Certain sub-variations outperform their parent openings significantly.  

---

## 🙌 Acknowledgments
- Dataset source: https://www.kaggle.com/datasets/alexandrelemercier/all-chess-openings  
- Tools: Python, Power BI  
