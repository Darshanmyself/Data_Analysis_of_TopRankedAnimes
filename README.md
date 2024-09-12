**Top Ranked Anime Data Analysis**

This project focuses on analyzing and extracting valuable insights from an anime dataset using SQL for database management and Tableau for visualization. The project aims to clean, normalize, and break down a large dataset into multiple interconnected tables, removing redundancy and missing values, before performing detailed data analysis.

**Project Overview**

**Problem Statement:**
The original dataset was unnormalized, contained null values, and exhibited data redundancy, making it difficult to analyze and extract insights efficiently. The objective was to clean, normalize, and restructure the dataset while establishing meaningful relationships between tables using foreign keys.

**Step-by-Step Breakdown**

**1. Dataset Overview:**
The dataset contained various features related to anime, such as broadcast times, genres, ratings, studios, and more. However, it was:
Containing null/missing values.
Not normalized, leading to data redundancy.
Lacking relational integrity across relevant fields.

**2. Data Cleaning:**
Handling Null Values: The dataset was examined for missing values, and necessary action was taken to either remove or impute these values.
Redundancy Removal: Duplicate and redundant data entries were identified and removed to avoid inconsistencies in the analysis.

**3. Data Normalization:**
The dataset was normalized to reduce redundancy and improve data structure by breaking it down into multiple tables. The aim was to ensure each table contained atomic data and followed the principles of First, Second, and Third Normal Form (1NF, 2NF, 3NF).

The dataset was split into the following tables:
anime_broadcast
anime_genre
anime_licensor
anime_producer
broadcast
genre
licensor
premiered
producer
rating
source
status
studios
type
These tables were connected using foreign keys to ensure referential integrity, meaning the relations between different entities in the dataset were properly maintained.

**4. Table Creation and Relationships:**
Each table was designed to store specific, non-redundant information.
Foreign keys were used to establish one-to-many and many-to-many relationships between tables, allowing for optimized queries and data retrieval.

**5. Data Analysis:**
Using SQL, various complex queries were executed on the normalized database to extract valuable insights about the anime data, including:
Most common genres across different anime.
Top-rated anime in each genre.
Popular studios producing high-rated anime.
Licensing companies associated with the most successful anime.
Rating distribution of anime based on broadcast time.
Seasonal trends in anime releases.

**6. Visualization Using Tableau:**
After performing SQL analysis, the results were imported into Tableau for data visualization. Key insights were visualized using various graphs and charts, making it easier to understand trends and patterns in the dataset.

**Technologies Used**

**SQL:** For data cleaning, normalization, and analysis. Complex queries to extract meaningful insights from a relational database.
**Tableau:** For creating interactive and dynamic visualizations.
