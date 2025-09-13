**Netflix Movies and Shows EDA**
This project performs exploratory data analysis (EDA) on the Netflix Movies and Shows dataset sourced from Kaggle, focusing on understanding trends, distributions, and patterns within Netflix's catalog over time.

**Dataset Source**
Dataset: netflix_titles.csv from Kaggle

Features examined: type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

**What Was Done**
Imported and inspected the dataset to understand the structure and missing data.

Performed EDA using matplotlib and seaborn for visualization.

Investigated content types, release years, country contributions, trends of added content, and rating distributions.

**MATPLOTLIB PLOTS**

**1. Movies vs TV Shows (Bar Plot)**
_Purpose:_ Compares the total count of Movies and TV Shows available on Netflix.
_Insight:_ Reveals which type of content is more dominant on the platform.

![Barplot](Screenshots/Barplot.png)


**2. Distribution of Movie Release Years (Histogram)**
_Purpose:_ Shows how movies are distributed across release years.
_Insight: _Identifies whether Netflix's library is skewed towards newly released movies or includes many classics.

![Histogram](Screenshots/Histogram.png)


**3. Top 5 Countries with Most Content (Pie Chart)**
_Purpose:_ Visualizes the share of Netflix content from the top five producing countries.
_Insight:_ Highlights the most prominent countries in Netflix’s catalog, showing levels of internationalization.

![Pie Chart](Screenshots/piechart.png)


**4. Trend of Content Added Over Years (Line Plot)**
_Purpose: _Shows how many titles were added each year to Netflix.
_Insight:_ Reveals periods of rapid expansion or slowdowns and trends in Netflix’s content growth strategy.

![Line Chart](Screenshots/linechart.png)


**5. Ratings Distribution by Content Type (Stacked Bar Plot)**
_Purpose:_ Compares ratings (TV-MA, PG, etc.) across Movies and TV Shows.
_Insight:_ Highlights the distribution of content maturity and age group focus by type.

![Stacked Bar](Screenshots/stackedbar.png)


**SEABORN PLOTS**


**6. Movies vs TV Shows (Seaborn Countplot)**
_Purpose:_ Provides an alternative visualization for the count of Movies and TV Shows using seaborn.
_Insight:_ Verifies and visually complements the results from the previous bar plot.

![Countplot](Screenshots/countplot.png)


**7. Distribution of Movie Durations (Histogram + KDE)**
_Purpose:_ Displays how movie durations (in minutes) are spread out, including a density curve for better shape analysis.
_Insight:_ Detects if most movies fall within a typical runtime or if there are many outliers (very short or long movies).

![Histogram + KDE](Screenshots/histogram+kde.png)


**8. Number of Seasons in TV Shows (Boxplot)**
_Purpose:_ Shows the spread and median of the number of seasons in Netflix TV shows.
_Insight:_ Identifies whether most shows are short series, or if there are many long-running ones.

![Boxplot](Screenshots/boxplot.png)


**9. Top 10 Genres on Netflix (Barplot)**
_Purpose:_ Displays which genres (first keyword for each) have the most titles on Netflix.
_Insight:_ Reveals popular genres and category focus of Netflix’s content.

![Seaborn Barplot](Screenshots/snsbarplot.png)


**10. Correlation Between Numeric Features (Heatmap)**
_Purpose:_ Shows how numeric features (release year, year added, duration, number of seasons, type) are correlated.
_Insight:_ Reveals relationships such as whether newer titles tend to be longer, or if more TV shows are added in recent years.

![Heatmap](Screenshots/heatmap.png)


**11. Movie Release Year vs Duration (KDE Plot)**
_Purpose:_ Kernel Density Estimate plot showing how movie duration varies with release year.
_Insight:_ Helps spot trends such as whether newer movies trend longer or shorter in duration.

![KDE](Screenshots/kde.png)
