# Save the README content as a Markdown (.md) file

readme_md = """# Korean Baseball Pitching Analysis

**Author:**  
Christian Huerta

## Purpose
The purpose of this project is to analyze professional pitching statistics from the Korean Baseball Organization (KBO). Through data exploration and visualization, the goal is to uncover trends and relationships in team and player performance, particularly in key pitching metrics.

## Research Questions
This analysis seeks to answer several questions, including:

1. What is the average ERA (Earned Run Average) across teams?
2. Is there a correlation between player age and ERA?
3. Which team averages the most runs per game?
4. How do teams compare in metrics like H/9, K/9, WHIP, and HR/9?
5. What is the distribution of wins, losses, wild pitches, and hit batters by team?

## Dataset Summary
- **File**: `Korean Baseball.csv`
- **Contents**: Pitching statistics for KBO teams, including metrics like ERA, WHIP, strikeouts, wild pitches, home runs allowed, and more.
- **Size**: Includes multiple teams and players with various season-level stats.

## Tools and Technologies
- **Jupyter Notebook**: For documenting and running the analysis.
- **Pandas**: For data manipulation and wrangling.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For plotting and visualization.
- **SciPy**: For statistical testing and correlations.

## Key Observations (So Far)
- Certain teams consistently outperform others in strikeouts and ERA.
- There appears to be a mild correlation between player age and ERA.
- Some teams show higher than average WHIP and home run rates, which may indicate pitching challenges.
- Wild pitches and hit batters vary widely across teams, showing different control profiles.
"""

readme_md_path = "/mnt/data/KBO_Pitching_README.md"
with open(readme_md_path, "w", encoding="utf-8") as f:
    f.write(readme_md)

readme_md_path
