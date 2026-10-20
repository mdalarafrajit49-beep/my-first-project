# Netflix Content Analysis using Excel

## Project Status
Completed

## Objective
Analyze the distribution of movies and TV shows,
content categories, and title additions over time
using Microsoft Excel.

## Dataset
Source: Kaggle — Netflix Movies and TV Shows
https://www.kaggle.com/datasets/shivamb/netflix-shows

## Tools Used
Microsoft Excel

## Data Cleaning
1.Remove the duplicate user id
2.Replace values from null to unknown for countries & directors
3.trimmed text of date added
4.Columb added of "Duration min" & "Seasons"
5.in another sheet just put "show id" and "country" & Remove the other columbs 
6.Now split columbs by delimeter
7.Change the type of "Country" & trimmed it
## Questions
## Analysis Questions

1. **Content Type:** Are there more movies or TV shows in the dataset?

2. **Countries:** Which are the top 10 countries associated with the most titles in the dataset?

3. **Content Added Over Time:** How many titles were added to Netflix each year, based on the `date_added` column?

4. **Genres and Categories:** Which genres or categories appear most frequently when entries in the `listed_in` column are counted separately?

5. **Content Ratings:** How are titles distributed across content rating categories such as TV-MA, PG-13, and TV-14?

6. **Duration:** What is the most common movie duration in minutes, and what is the most common number of seasons for TV shows?
## Method
1.We used pivot tables
2.We turn the values into percentage
3.We used pivot charts

## Findings
## Key Findings

### 1. Movies vs TV Shows
The cleaned dataset contains [8807] titles, including
[6131] movies (69.62%) and
[2676] TV shows (30.38%).
Movies  are the larger share of titles.

### 2. Top Countries
[united states] is associated with the highest number of titles
([3699]), followed by [India] (1046) and
[unknown] (831).

Titles associated with multiple countries were counted
once for each listed country.

### 3. Titles Added Over Time
Based on the available `date_added` values, [2018] recorded
the highest number of title additions, with [1147] titles.
Annual additions [The number of titles were increasing untill 2018 but it fell to 1925 by 2021] during
[1925 to 2021].

### 4. Genres and Categories
[Dramas, International Movies] is the most frequently listed category,
appearing in [362] titles. It is followed by
[Documentaries] ([359]) and [Stand-Up Comedy] ([334]).

Each category was counted separately for titles with
multiple entries in the `listed_in` column.

### 5. Content Ratings
[TV-MA] is the most common content rating,
with [3207] titles, followed by [TV-14]
with [2160] titles.

### 6. Movie Duration and TV Show Seasons
The most common movie duration is [90] minutes,
shared by [152] movies.

For TV shows, [01]-season titles are the most common,
with [1793] titles.

## Files
- https://1drv.ms/x/c/7e10cac2ae4d4283/IQBI11INGY_QTYFvdK20Yvp4AfbPY2LyVi5nUZbgBl6lso8?e=i1tdea

## Limitations
This analysis describes the dataset used,
not Netflix's current live catalog.
Title counts do not measure viewing popularity.
