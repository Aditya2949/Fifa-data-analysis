## ⚽ FIFA World Cup Player Data Analysis
-A data analysis project exploring FIFA player statistics using Python, Pandas, Matplotlib, and Seaborn. This project dives into player attributes like nationality, wages, shooting, defending, and club-level insights — uncovering patterns from a dataset of over 16,000 professional football players.

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the FIFA player dataset sourced from SoFIFA. It covers a wide range of analyses including player nationality distribution, salary rankings, skill comparisons, and club-specific breakdowns.

## 📂 Dataset

- File: fifa.csv
- Rows: 16,155 players
- Columns: 81 features
- Source: SoFIFA (FIFA video game player data)

## Key attributes include:
- Player identity: short_name, long_name, nationality, age, dob
- Club info: club_name, league_name, league_rank
- Performance: overall, potential, shooting, defending, dribbling, passing, pace
- Physical: height_cm, weight_kg
- Financial: wage_eur, value_eur, release_clause_eur
- Detailed skill stats: 40+ granular attributes (e.g., attacking_finishing, goalkeeping_reflexes)

## Analysis Performed
1. Nationality Distribution
  - Counted players by nationality across 149 countries
  - Visualized the Top 5 nationalities using a bar chart
  - England leads with 1,627 players, followed by Spain, France, Argentina, and Italy

2. 💰 Player Salary Analysis
- Extracted player wages and sorted in descending order
- Top earners: L. Messi (€550,000/week), Cristiano Ronaldo (€375,000/week), M. Neuer, L. Suárez
- Visualized top 5 highest-paid players with a color-coded bar chart

3. 🇩🇪 Germany National Team Deep Dive
- Filtered all German players from the dataset
- Ranked by:
    - Height — Tallest players: T. Stuckmann (199 cm), B. Pliquett (199 cm)
    - Weight — Heaviest: T. Wiese (110 kg), L. Unnerstall (100 kg)
    - Wage — Highest paid: M. Neuer (€300,000), M. Hummels & B. Schweinsteiger (€200,000 each)

4. 🎯 Shooting Ability Ranking
  - Extracted and ranked players by shooting score
  - Top shooters: Cristiano Ronaldo (93), Z. Ibrahimović (91), R. van Persie (90), L. Messi (89)

5. 🛡️ Defending Ability Ranking
   - Ranked players globally by defending score
   - Best defenders: Thiago Silva (90), M. Benatia (88), M. Hummels (88)
     
6.  Real Madrid Club Analysis
   - Filtered all Real Madrid players
   - Analyzed by:
           - Wages — Cristiano Ronaldo tops the list
           - Shooting — Ronaldo, Benzema, G. Bale lead
           - Defending — Sergio Ramos (87), Pepe (86) are the best defenders
           - Nationality breakdown — Spain (17), Portugal (3), Germany (2), France (2)

7. Key Insights
   - England has the most professional FIFA-rated players globally.
   - Lionel Messi earns the highest weekly wage at €550,000.
   - Cristiano Ronaldo has the highest shooting rating (93) among all players.
   - Thiago Silva is the top-rated defender in the dataset.
   - Real Madrid squad consists of players from 12 different nationalities, with Spain being the most represented.

## Author -
  Aditya Patil
  
  📧 Email:adityapatil2949@gmail.com
  
  Linkedin: https://www.linkedin.com/in/aditya-patil-7047512a1/
