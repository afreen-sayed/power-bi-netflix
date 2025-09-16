Netflix Content Analysis Dashboard (Power BI)

Objective :
The goal of this project was to analyze Netflix’s catalog of Movies and TV Shows to uncover insights into content distribution, genre preferences, ratings, and release trends across countries and years. The project transforms raw Netflix data into an interactive Power BI dashboard that allows users to explore patterns and make data-driven conclusions about Netflix’s content strategy.

Data Source :
The dataset was sourced from Kaggle.
Data cleaning and transformation were performed in Power Query:
    Blank or missing values in fields like Director and Country were handled.
    Genre column was normalized using a secondary file.
    Columns such as Duration and Seasons were separated to differentiate Movies from TV Shows.
    Null entries were replaced with “Not Mentioned” for better filtering and visualization.

Dashboard Overview :
The Netflix Dashboard provides an interactive snapshot of global Netflix content. It includes slicers for Release Year, Month, and Country, enabling users to filter and view trends dynamically.

Key Highlights :
    KPIs:
        Total Titles: 8,321
        Countries Covered: 83
        Top 5 Directors: Highlighting directors with the most Netflix titles.
        Genre Distribution: Bar chart showcasing top genres with highest counts.
        Movies vs TV Shows by Country: Comparison of distribution across countries.
        Most Common Ratings: Donut chart of TV/Film ratings (TV-MA, TV-14, PG-13, etc.).
        Release Trends: Line chart showing Movies & TV Shows released over the years.
        Duration Analysis: Histogram of movie durations by rating.
        Overall Split: Donut chart of Movies vs TV Shows (68% Movies, 32% TV Shows).

Business Insights & Recommendations :
    Content Type Preference: Movies dominate Netflix’s catalog (68%), but TV Shows are steadily growing in recent years.
    Global Reach: U.S. and India lead in Netflix content production, suggesting focus markets.
    Ratings Distribution: TV-MA and TV-14 are the most common, indicating mature audiences as the target segment.
    Genre Diversity: International Movies and Dramas are the most popular categories—expanding such genres can attract larger     audiences globally.
    Historical Trend: Post-2015, Netflix content has grown rapidly, peaking around 2018–2020, aligning with global expansion      strategy.
