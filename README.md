# FIFA World Cup Interactive Dashboard ⚽🏆

## Project Overview
This interactive visualization tool was designed for the exploration and analysis of FIFA World Cup history[cite: 6, 74]. Using two datasets from the Tidy Tuesday collection (`worldcups.csv` and `wcmatches.csv`), the dashboard enables users to analyze team performance, attendance trends, and scoring evolution[cite: 63, 64, 65].

## Key Visualizations
* **Lollipop Chart:** Displays total World Cups won by country, using minimalist design to focus on relative differences.
* **Scatter Plot:** Visualizes attendance over time, highlighting tournament-specific outliers.
* **Bar + Scatter Plot:** Tracks the evolution of goals scored vs. games played per tournament.
* **Heatmap with Icons:** A temporal comparison of matches won per tournament by the top 10 countries, featuring trophy icons for championship years.

## Technical Implementation
- **Language:** Vega-Lite (JSON).
- **Interactivity:** Integrated country filters and year sliders using Vega-Lite parameters to ensure a fast, responsive user experience
- **Tooltip Integration:** Hover features provide precise data values without cluttering the visual field

## Insights Gained
The dashboard allows users to identify periods of country dominance, such as Brazil's consistent performance, and observe how changes in tournament formats impacted overall goal-scoring rates.