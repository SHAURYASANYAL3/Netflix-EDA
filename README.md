# Netflix Movies & TV Shows - Exploratory Data Analysis

## Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the Netflix dataset as part of the Pluto Academy Internship Project 01. The objective is to uncover underlying patterns in content production, geographical distribution, release trends, and audience targeting.

## Objectives
- Understand dataset structure and metadata
- Conduct rigorous data cleaning (e.g., extracting precise durations for TV shows vs. movies)
- Perform feature engineering
- Explore content trends and distributions
- Generate high-quality, professional visualizations
- Derive highly detailed business and research insights

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Top 10 Business Insights & Recommendations
1. **Content Mix Strategy**: Movies constitute roughly 69% of the library, while TV Shows make up 31%. While movies are dominant, the high engagement of serialized content suggests Netflix should continue accelerating its original TV Show investments to foster long-term subscriber retention.
2. **Geographical Dominance**: The US overwhelmingly dominates content production, followed by India and the UK. Netflix should maintain its aggressive push into the Indian market, while exploring untapped markets in Latin America and Africa for diverse international growth.
3. **The 2019 Peak**: Content additions saw exponential growth until peaking in 2019, followed by a noticeable decline. This drop reflects pandemic-era production halts. Moving forward, Netflix should balance rapid volume growth with a focus on higher-quality releases.
4. **Target Demographics**: TV-MA and TV-14 are the most prevalent ratings. The platform is heavily skewed towards mature demographics. To capture broader household subscriptions, expanding the Kids & Family portfolio is recommended.
5. **Movie Duration Standardization**: The vast majority of movies fall exactly into the 90-100 minute "sweet spot." Creators pitching to Netflix should target this optimal length, as it aligns with viewer completion rates.
6. **The "One-and-Done" TV Show Phenomenon**: Most TV Shows end after just 1 Season. To reduce subscriber churn, there should be a strategic focus on renewing successful shows for multi-season arcs to build loyal fandoms.
7. **Genre Popularity**: International Movies, Dramas, and Comedies are the top three genres. The massive success of "International Movies" proves that local-language content travels globally.
8. **Recent Content Bias**: Netflix's library is heavily skewed toward content released after 2010. Curating a "Classic Cinema" tier could attract cinephiles and older demographics who feel underserved.
9. **Release Strategies**: Content additions spike slightly in December, January, and October. Netflix capitalizes on holiday binge-watching and should continue releasing their highest-budget original content precisely during these seasonal peaks.
10. **Data Completeness**: Significant missing data exists in the `director` and `cast` columns. Netflix engineering teams must enforce stricter metadata requirements during content ingestion for better recommendation algorithms.

## Most Surprising Finding
**The dominance of 1-Season TV Shows.** Given the cultural impact of long-running shows like *Stranger Things*, it is highly surprising that the vast majority of TV shows on the platform do not make it past their first season. This highlights a ruthless "fail-fast" cancellation culture or a massive pivot toward "Limited Series" formats.

## Files
- `netflix_eda.ipynb` — Complete analysis notebook
- `netflix_titles.csv` — Raw dataset
