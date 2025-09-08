Premier League Statistical Analysis Project — Sub-project 1: Historical Player Performance Analytics

Premier League player performance analytics using end-of-season FBRef data (2023/24 and 2024/25).  
This project builds a foundation for exploring, cleaning, and visualizing football data before moving toward predictive models in later repos.

---

## Goal
Analyze historical player performance over the past 2 seasons and create clear visualizations to compare output across players and roles.

---

## Tasks

1. **Data Preparation**
   - Load and clean end-of-season player data (23/24 + 24/25).
   - Standardize column names (e.g., `Gls`, `Ast`, `xG`, `xAG`).
   - Compute per-90 metrics:
     - Goals/90
     - Assists/90
     - G+A/90
     - xG/90, xAG/90

2. **Comparisons Across Seasons**
   - Identify top players in key metrics (Goals, Assists, Progressive actions).
   - Compare returning stars vs breakout players.

3. **Visualizations**
   - **Scatter plots:** xG vs Goals (over/underperformance).
   - **Bar charts:** Top 10 Assist leaders vs xAG.
   - **Radar charts:** Season profiles for standout players.

4. **Output**
   - Historical dashboards summarizing how stars and breakout players performed across 2 seasons.
   - Jupyter Notebook with analysis and plots.

---

## 🛠 Tech Stack
- **Python**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly (optional for interactivity)
- **Environment**: Jupyter Notebook

---

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/prem-project-1-historical.git
   cd prem-project-1-historical
