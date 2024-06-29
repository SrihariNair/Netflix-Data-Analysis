# Netflix Data Analysis ELT Project

This project involves the extraction, transformation, and loading (ETL) of Netflix data to analyze various aspects such as the number of movies and TV shows created by directors, the impact of genre on movie durations, and identifying key patterns in the dataset. The project normalizes the main data table into smaller tables, handles null values, removes duplicates, and performs comprehensive data analysis.

## 🌐Business problem

Decision-makers at Netflix need to understand various factors affecting the viewership and production of their content. Insights into director contributions, genre preferences, and country-specific trends are crucial for strategic planning and content curation.

## 📝Analytics Problem

In this project, we analyzed the Netflix dataset to break down how different directors contribute to various genres, the distribution of comedy movies across countries, and the average duration of movies per genre. By normalizing the dataset and handling null values, we ensured accurate and meaningful analysis.

## 📈Analysis Performed:

In this project, we focused on analyzing Netflix data to answer the following questions:

- **Director Analysis**: Identify directors who have created both movies and TV shows, and count the number of each they have produced.

- **Country Analysis**: Determine which country has the highest number of comedy movies.

- **Yearly Director Analysis**: For each year, identify the director who has released the maximum number of movies.

- **Genre Duration Analysis**: Calculate the average duration of movies within each genre.

- **Cross-Genre Director Analysis**: Find directors who have created both horror and comedy movies, and display the number of each genre directed by them.

By transforming the raw data into a structured format, we ensure high-quality data analysis, providing Netflix with actionable insights into their content library.

## Key Steps Involved:
1. **Create Staging Table**: Structure the main table to store Netflix data.
2. **Delete Duplicates**: Remove duplicate records based on type and title.
3. **Normalize Tables**: Split the main table into smaller, focused tables (director, country, cast, genre).
4. **Handle Null Values**: Fill missing data in critical fields like country and duration.
5. **Create Final Table**: Consolidate the cleaned and structured data into a final table for analysis.
6. **Perform Data Analysis**: Execute SQL queries to answer key business questions about Netflix's content.

This comprehensive approach enables Netflix to leverage its data for strategic decisions, ensuring a robust understanding of content production and viewership trends.
