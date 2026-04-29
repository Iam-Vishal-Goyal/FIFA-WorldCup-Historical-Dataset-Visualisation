# FIFA World Cup Interactive Dashboard ⚽🏆

![Dashboard Screenshot](Visualisation.jpg)

## Project Overview
[cite_start]This interactive visualization tool was designed for the exploration and analysis of FIFA World Cup history[cite: 6, 74]. [cite_start]Using two datasets from the Tidy Tuesday collection (`worldcups.csv` and `wcmatches.csv`), the dashboard enables users to analyze team performance, attendance trends, and scoring evolution[cite: 63, 64, 65].

## Key Visualizations
* [cite_start]**Lollipop Chart:** Displays total World Cups won by country, using minimalist design to focus on relative differences[cite: 79, 81].
* [cite_start]**Scatter Plot:** Visualizes attendance over time, highlighting tournament-specific outliers[cite: 87, 88].
* [cite_start]**Bar + Scatter Plot:** Tracks the evolution of goals scored vs. games played per tournament[cite: 94, 95].
* [cite_start]**Heatmap with Icons:** A temporal comparison of matches won per tournament by the top 10 countries, featuring trophy icons for championship years[cite: 101, 106].

## Technical Implementation
- **Language:** Vega-Lite (JSON).
- [cite_start]**Interactivity:** Integrated country filters and year sliders using Vega-Lite parameters to ensure a fast, responsive user experience[cite: 112, 114].
- [cite_start]**Tooltip Integration:** Hover features provide precise data values without cluttering the visual field[cite: 115].

## Insights Gained
[cite_start]The dashboard allows users to identify periods of country dominance, such as Brazil's consistent performance, and observe how changes in tournament formats impacted overall goal-scoring rates[cite: 72, 78, 97].