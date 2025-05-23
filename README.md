# Cubs vs. White Sox Score Simulation Project

This project simulates the outcome of a baseball game between the **Chicago Cubs** and **Chicago White Sox** using three progressively detailed models:
1. **Team-Level Historical Score Model**
2. **Player-Level Statistical Aggregation Model**
3. **Injury-Adjusted Simulation Model**

The simulation estimates expected runs, win probabilities, and score distributions using real-world data and statistical modeling techniques.

---

## 📂 Files Included

- `player_stats_2024.csv` – Real batting and pitching stats for key Cubs and White Sox players.
- `injury_replacements_2024.csv` – Injured players and their statistical replacements.
- `model_1_team_level.py` – Poisson-based simulation using historical team-level scores.
- `model_2_player_level.py` – Score estimation based on player performance aggregates.
- `model_3_injury_simulation.py` – Monte Carlo simulation accounting for injuries and replacements.
- `README.md` – Project documentation.

---

##  Models Overview

### Model 1: Historical Team Score Simulation
- Uses average historical scores from the past two years.
- Poisson distribution used to simulate game outcomes.

### Model 2: Player Performance-Based Prediction
- Aggregates batting average, HR, RBI, and ERA for each team.
- Estimates expected runs from these statistics.

### Model 3: Injury-Adjusted Simulation
- Replaces injured players with substitutes based on real data.
- Computes updated expected scores and win probabilities using simulation.

---

## Running the Models

1. Install dependencies:
```bash
pip install pandas numpy matplotlib scipy scikit-learn
