# 🎬 Movies Database – SQL Analysis (MySQL)

Solving 31 questions (easy → hard) on an IMDb-style movies database.

## Dataset
6 CSV files: Movies, Ratings, Genre, Actors, Role_Mapping, Director_Mapping.

## Skills Used
- Filtering & sorting (WHERE, LIKE, IN, BETWEEN, ORDER BY)
- Aggregations (GROUP BY, COUNT, AVG, SUM)
- Joins across multiple tables
- Subqueries & CTEs
- Window functions (RANK, DENSE_RANK, PARTITION BY)
- CASE statements
- Data cleaning (STR_TO_DATE, removing currency symbols)

## Files
- `Movie_Dataset.sql` – table setup + all 31 queries
- `DATA/` – the 6 CSV files
- `LIST_OF_QUESTIONS.pdf` – the questions

## How to Run
1. In `Movie_Dataset.sql`, change the `LOAD DATA INFILE` paths to where your CSVs are saved.
2. Run the file in MySQL Workbench.

## Key Insights
- Drama is the most common genre (4,285 movies), then Comedy (2,412).
- Thriller ranks #3 by number of movies.
- A24 produced the most hit movies (avg rating > 7).

## Author
Darshan K. Vaghela | LinkedIn : https://www.linkedin.com/in/darshanvaghela9
