# TNSA -- Tableau Netflix Sample Analysis

**TNSA** is an interactive Tableau dashboard built to analyze a
randomized sample of Netflix content data.

## Dataset

-   Source: [Kaggle Netflix Dataset](https://www.kaggle.com)\
-   Size: \~6,000+ titles (movies and shows)\
-   Preparation: Data was cleaned and joined in **Tableau Prep**,
    including:
    -   Removing duplicates with calculated fields\
    -   Handling null values and fixing data types\
    -   Simplifying year ranges for easier filtering\
    -   Standardizing country names (e.g., merging *USSR* into
        *Russia*)\
    -   Randomizing the dataset to create a balanced analysis sample

## Dashboard Design

The dashboard consolidates **7 key visualizations**, styled with a black
background and red accents to reflect the Netflix brand.

**Included Visuals:**\
- List of movies and directors\
- Time difference between release date and Netflix listing date\
- Count of titles by age rating\
- Title listings by year\
- Bubble chart of category distribution\
- Line chart of categories over time\
- Map of category distribution by country

All charts are **color-coded by category** for quick insights.

## Key Insights

-   **Top Genres:** Dramas, Comedies, Thrillers, and International
    Movies dominate Netflix listings.\
-   **International Presence:** International movies are heavily
    represented, with a large share coming from India.\
-   **Growth Trend:** Netflix listings surged between **2017--2019**,
    especially in dramas and comedies.\
-   **Ratings:** **TV-MA** is the most common movie rating across the
    dataset.

## Notes

-   This dashboard uses a **randomized sample of the original dataset**
    and focuses exclusively on movies.\
-   Despite sampling, the analysis reflects clear **general trends** in
    Netflix content.
