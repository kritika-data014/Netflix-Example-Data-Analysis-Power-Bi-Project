# Netflix Content Analysis with Power BI
## Project Overview
This Power BI project focuses on end-to-end data cleaning and preparation. Key steps include:

**Column profiling** to understand data structure

**Handling missing values** by encoding and imputing nulls

**Cleaning date fields** and creating derived time-based columns

**Generating new columns** for analysis (e.g., category, region)

**Splitting and extracting values** from multi-entry fields

**Performing text/sentiment analysis** on descriptive fields

**Filtering out irrelevant data** to streamline the dataset

These steps ensure the dataset is analysis-ready, enabling clear and meaningful visual insights.

## Dataset
- Source: [Kaggle Netflix Dataset](link-to-kaggle)
- Contains: ID, Title, Type, Genre(s), Release Year, Duration, Rating, Country, Added Date, etc.

## Business Questions
1. Which genres are trending?
2. How does content length differ by type?
3. How do ratings correlate with duration?
4. What are the country-level production and success patterns?
5. Are there seasonal content-adding trends?

## Tools & Workflow
- Power BI Desktop for data modeling and visualization.
- Power Query: ETL tasks.
- DAX: Calculated measures (Avg Duration, Count per Country).
- Visualizations: Charts, maps, scatter and KPIs.

## Insights
- E.g., "Documentaries have increased by 30% since 2018."
- "Longest movies tend to have slightly higher ratings, but not uniformly across genres."

## How to Run
1. Clone repo
2. Open `Netflix_Analysis.pbix` in Power BI Desktop (>= July 2025)
3. Ensure dataset file is in `/data/` folder.
4. Refresh data and explore.

## Files
- `/data/netflix_cleaned.csv`
- `/Netflix_Analysis.pbix`

## Contact
Email: kritimahajan014@gmail.com

LinkedIn: https://www.linkedin.com/in/kritika-mahajan-014contact
