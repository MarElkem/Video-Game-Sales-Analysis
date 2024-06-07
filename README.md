# MSCS 164B Final Project: Video Game Trends

## Project Details
**Title:** MSCS 164B Final Project: Video Game Trends  
**Author:** Maroova Elkemary  
**Output Format:** HTML Document  
**Theme:** Sketchy (Bootswatch)  
**Data Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales) scraped from [vgchartz.com](http://www.vgchartz.com/)

## Introduction

This project conducts a comprehensive analysis of the video game industry's evolution from its inception in 1958 with "Tennis for Two" to its current status as a multi-billion dollar industry. The analysis focuses on trends from 2010 to 2016, examining genres, sales, and reviews to uncover patterns in video game popularity and critical reception.

## Dataset Overview

The data includes information on video games with sales exceeding 100,000 copies, encompassing attributes such as year of release, genre, regional sales, and review scores. This dataset facilitates a nuanced look at the dynamics of the video game market over the specified period.

## Technical Framework

### Tools and Libraries Used
- **R Programming Language:** Utilized for all data manipulation, analysis, and visualization tasks.
- **Tidyverse:** A collection of R packages including `dplyr`, `ggplot2`, `readr`, and more for data manipulation and graphical representation.
- **Plotly:** Integrated for interactive visualizations.
- **Shiny:** Employed to create interactive web applications directly from R.
- **Viridis:** Used for colorblind-friendly palettes in visualizations.
- **Gganimate:** For creating animations of time-series data to show trends over time.
- **Knitr:** Utilized for dynamic report generation in R Markdown.

### Data Manipulation
- **Data Cleaning:** Renaming variables for clarity, converting data types, and handling missing values.
- **Aggregation:** Summarizing data to analyze trends at different levels, such as by year or genre.
- **Transformation:** Normalizing scores to ensure comparability across different scales.

### Visualization Techniques
- **Bar Graphs and Line Charts:** For trends in genre popularity and sales over time.
- **Scatter Plots:** To analyze the relationship between critic and user scores versus sales.
- **Heatmaps and Ridge Plots:** For detailed density distributions of scores and sales.

### Interactive Elements
- **Plotly Integration:** To enhance user engagement through interactive charts that allow for deeper exploration of the data.
- **Shiny App:** Providing a dynamic way for users to explore data based on their inputs and interests.

## Analysis Highlights

### Genre Popularity Analysis
Explored the changing preferences in video game genres, highlighting the sustained dominance of action games and the impact of major releases like GTA 5.

### Platform Trends
Compared major gaming platforms, focusing on the rivalry between PlayStation and Xbox, and examined the rise of mobile gaming.

### Review Impact Study
Investigated how the critical and user reviews correlate with the financial success of games, identifying trends in how public perception influences sales.

### Publisher Sales Performance
Analyzed top publishers based on global sales, uncovering the strategies and titles that led to market success.

## Conclusion

The project concludes with insights into the factors that drive success in the video game industry, from genre popularity and platform choice to the critical reception of games. The findings provide a foundation for understanding market dynamics and can guide future studies on consumer behavior in the gaming industry.

## References

- Video Game Sales Dataset: [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)
- Initial video game history: [Brookhaven National Laboratory](https://www.bnl.gov/about/history/firstvideo.php)
- Game Awards viewership statistics: [The Washington Post](https://www.washingtonpost.com/entertainment/video-games/2023/12/08/game-awards-winners-losers/)
