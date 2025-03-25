# Netflix Data Analysis using SQL

## Overview
This repository contains SQL queries designed to analyze a Netflix dataset. The queries help extract meaningful insights from the dataset, including content distribution, ratings, directors, actors, and more.

## Dataset Schema
The dataset consists of the following columns:
- `show_id`: Unique identifier for each show
- `type`: Whether the content is a Movie or TV Show
- `title`: Name of the content
- `director`: Director(s) of the content
- `casts`: List of actors
- `country`: Country of origin
- `date_added`: Date when the content was added to Netflix
- `release_year`: Year of release
- `rating`: Content rating (e.g., PG, R, TV-MA)
- `duration`: Duration of movies or number of seasons for TV Shows
- `listed_in`: Genre(s) associated with the content
- `description`: Short description of the content

## SQL Queries and Insights
### Key Analyses:
1. **Count of Movies and TV Shows** - Determine the total number of Movies and TV Shows.
2. **Most Common Ratings** - Identify the most frequent ratings for Movies and TV Shows.
3. **Movies Released in a Specific Year** - Fetch all movies released in a given year.
4. **Top 5 Countries with Most Content** - Find the countries contributing the most to Netflix's library.
5. **Longest Movie Duration** - Identify the movie with the longest runtime.
6. **Content Added in the Last Five Years** - Retrieve content added recently.
7. **Content by a Specific Director** - List all shows directed by 'Rajiv Chilaka'.
8. **TV Shows with More than 5 Seasons** - Fetch TV Shows with more than 5 seasons.
9. **Genre-wise Content Count** - Categorize content based on genre.
10. **Average Number of Content Released by India per Year** - Analyze content trends in India.
11. **Documentaries on Netflix** - Retrieve all documentary content.
12. **Content Without a Director** - Find shows that lack director information.
13. **Movies Featuring 'Salman Khan' in the Last 10 Years** - Identify recent movies featuring Salman Khan.
14. **Top 10 Actors in Indian Movies** - List actors appearing in the most movies in India.
15. **Content Categorization Based on Keywords** - Categorize content as 'Good' or 'Bad' based on keywords like 'kill' and 'violence' in the description.

## Usage
To execute these queries, load the dataset into a PostgreSQL-compatible database and run the SQL commands sequentially.

## Contribution
Feel free to contribute by improving queries, optimizing performance, or adding new insights.

## License
This project is open-source and available under the MIT License.

