# TSGA -- Tableau Steam Game Analysis

**TSGA** is an interactive Tableau dashboard analyzing the **Top 100
Most Played Steam Games** (snapshot from August 2024). The dataset was
enriched by joining with the **games-features** dataset, which contains
detailed data on over 13,000 games.

## Dataset

-   Sources:
    -   [Top 100 Played Steam Games (August 2024) --
        Kaggle](https://www.kaggle.com)\
    -   [Games-Features Dataset -- Kaggle](https://www.kaggle.com)\
-   Data Preparation: Performed in **Tableau Prep**, including:
    -   Rounding and converting game prices from GBP → USD\
    -   Renaming and standardizing fields\
    -   Parsing genre tags string into multiple columns for detailed
        genre analysis\
    -   Left-joining with *games-features* dataset to add more
        attributes (e.g., age rating, release date, Metacritic score,
        recommendation count)\
    -   Creating a calculated field `Supported Languages` to parse
        language strings and generate a count of supported languages

## Dashboard Design

The dashboard combines **8 key visualizations**, styled with a **black
background** for clarity and thematic consistency.

**Included Visuals:**\
- List of games with rankings\
- Average analysis using binned statistics\
- Treemap of games by player count\
- Bar chart of genres\
- Bar chart of most recommended games\
- Scatter plot: Recommendations vs Player Count\
- Scatter plot: Price vs Player Count\
- Scatter plot: Recommendations by Genre vs Player Count

## Key Insights

-   **Dominant Title:** *Counter-Strike 2* leads significantly with
    **31M players**, nearly double *PUBG* at 16M.\
-   **Popular Genres:** *Multiplayer* and *Action* are the most common
    tags among the top 100 games.\
-   **Most Recommended:** *Dota 2* holds the top spot for
    recommendations.\
-   **High Average Players:** *Marvel Rivals* shows the highest average
    player count while being free-to-play.\
-   **Genre Trends:** *Fantasy* leads in recommendations, while
    *Trading* games attract the largest player counts.
