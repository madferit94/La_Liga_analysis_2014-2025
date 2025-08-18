# La_Liga_analysis_2014-2025

This project provides a historical analysis of goal-scoring metrics for all teams in La Liga across the last 11 seasons. 
It offers insights into the long-term attacking performance and trends throughout the league. 
Future updates are planned to incorporate defensive metrics.


# La Liga Big 3 Analysis (2014–2025)

Season-by-season analysis for Real Madrid, Barcelona, and Atletico Madrid using data derived from Understat.  
Current focus: Goals For (GF) and Expected Goals For (xGF).  
Planned extensions: defensive metrics (GA/xGA), Points Per Game (PPG) trends, and Big-3 head-to-head.

---

## Data Source

- **Source:** Understat — advanced football metrics (xG, shots, etc.)  
- **URL:** https://understat.com  
- **Coverage used:** La Liga seasons 2014–2025  
- **Acquisition:** Programmatically collected by the author for research/education.  
- **Usage note:** Shared for **educational, non-commercial** purposes. Please respect Understat’s Terms of Service.  
  If the data owner requests removal, this repository will comply.

> Acknowledgement: Original data © Understat. This project is not affiliated with or endorsed by Understat.

---

## 📊 Recent Update (2025-08-16)

- Added new Jupyter Notebook: `notebooks/la_liga_analysis_v01.ipynb`
- Included **Attack Efficiency (공격 효율성)** metric:
  - Formula: `GF per match - xGF per match`
  - Season total xGF = sum of all match-level xG
  - Positive value → efficient finishing, Negative → inefficient
- Visualization of Big 3 (Real Madrid, Barcelona, Atletico Madrid) attack efficiency trend by season

## Updates((2025-08-18)
- Added a new notebook in the `notebooks/` folder that includes defensive metrics analysis.
