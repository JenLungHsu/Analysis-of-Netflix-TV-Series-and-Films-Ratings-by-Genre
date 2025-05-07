# Analysis of Netflix TV Series and Films Ratings by Genre

## Project Overview
This project analyzes the ratings of TV series and films across various genres on Netflix. Through comprehensive data collection, pre-processing, Analysis of Variance (ANOVA), and Post-hoc analysis, the study investigates audience rating differences to identify genres with higher audience ratings. These insights aim to aid content creators in understanding audience preferences within the streaming entertainment sector.

## Dataset
- **Source:** [Netflix Engagement (Jan-Jun 23) - Kaggle](https://www.kaggle.com/datasets/vassyesboy/netflix-engagement-jan-jun-23)
- The dataset includes Netflix TV series and films, with a focus on genres that have more than 100,000 ratings.

## Research Objective
The primary objective of this analysis is to:
- Identify genres that consistently receive higher ratings on Netflix.
- Understand audience preferences and engagement across different content genres.
- Provide insights for strategic content creation on streaming platforms.

## Methodology
The study follows these steps:
1. **Data Preprocessing**
   - Removal of missing values and duplicates.
   - Selection of movies and TV series with over 100,000 ratings.
   - Sampling of 20 ratings per genre to balance representation.

2. **Statistical Analysis**
   - **ANOVA (Analysis of Variance)** to test for significant differences between genres.
   - **Post-Hoc Analysis (Tukey's HSD)** to identify specific genre pairs with significant differences.

3. **Assumption Testing**
   - Homogeneity of variance using Levene's and Bartlett's tests.
   - Normality assessment with Shapiro-Wilk and Lilliefors tests.

## Key Findings
- Genres like **War**, **History**, **Family**, and **Drama** tend to receive higher ratings.
- In contrast, **Horror** and **Sci-Fi** are among the lowest-rated genres.
- The post-hoc analysis allowed us to identify specific genres that exhibited significant differences in audience ratings.

## Usage
To view the analysis, simply open the provided PDF report:
```
RE6121011徐仁瓏_ANALYSIS OF NETFLIX TV SERIES AND FILMS RATINGS BY GENRE.pdf
```

## Project Structure
```
├── NF.ipynb
├── Netflix Engagement (plus).csv
├── RE6121011徐仁瓏_ANALYSIS OF NETFLIX TV SERIES AND FILMS RATINGS BY GENRE.pdf
├── README.md
```

## Contact
- **Author:** Jen Lung Hsu
- **Email:** RE6121011@gs.ncku.edu.tw
- **Institute:** National Cheng Kung University, Institute of Data Science
