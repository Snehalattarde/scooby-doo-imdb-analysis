# Scooby-Doo IMDb Ratings Analysis
Analysis of IMDb ratings for Scooby-Doo episodes using R and ANOVA

## Project Overview
This project analyzes IMDb ratings of *Scooby-Doo* television episodes to explore how audience ratings vary over time, episode format, and television network. The analysis emphasizes data cleaning decisions, exploratory visualization, and statistical inference using ANOVA.

The project is structured as a **problem set**, with clearly defined analytical questions followed by code, results, and interpretation.

---

## Research Questions
1. How have IMDb ratings of Scooby-Doo episodes changed over time?
2. Do different episode formats (e.g., segmented vs non-segmented TV episodes) affect IMDb ratings?
3. Should movies and crossover episodes be included when comparing TV series ratings?
4. Do IMDb ratings differ across television networks?
5. Are observed differences in average IMDb ratings across networks statistically significant?

---

## Data Source
The dataset comes from **TidyTuesday (2021-07-13)** and includes metadata and IMDb ratings for Scooby-Doo episodes aired across multiple decades and networks.

---

## Methodology
- **Data Cleaning**
  - Removed movies and crossover episodes to ensure fair comparisons
  - Aggregated segmented TV episodes to avoid inflating episode counts
- **Exploratory Data Analysis**
  - Visualized IMDb ratings over time and by network
  - Computed summary statistics by network
- **Statistical Analysis**
  - Conducted a one-way ANOVA to test for differences in mean IMDb ratings across networks
  - Applied Tukey’s HSD post-hoc test to identify which networks differed significantly

---

## Key Findings
- IMDb ratings vary over time and across networks.
- Certain networks exhibit higher average IMDb ratings than others.
- ANOVA results indicate whether these differences are statistically significant rather than due to random variation.

---

## Tools & Libraries
- R
- tidyverse
- ggplot2
- readr

---

## Files in This Repository
- `scooby_problem_set.Rmd` – R Markdown problem set with code, analysis, and interpretation
- `scooby_problem_set.html` – Rendered HTML report
- `README.md` – Project overview and documentation

---

## Author
**Snehal Attarde**  
Master’s in Information Technology  
Florida State University

