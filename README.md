# IPL_PROJECT

## Introduction

This project aims to analyze Indian Premier League (IPL) cricket data to evaluate team performance, match trends, and key business metrics.

The system integrates:

- Relational Database (MySQL)
- Python Data Analysis (Pandas)
- Data Visualization (Matplotlib)

The goal is to provide insights on team dominance, scoring patterns, match outcomes, and venue impact.


## Problem Statement

The project addresses the following analytical problems:

- Identify teams with the highest wins  
- Analyze wins by venue and season  
- Calculate average runs per match  
- Identify matches with no result  
- Compare home vs away performance  
- Analyze runs and wickets per match  
- Identify high-scoring matches  
- Determine top teams by win percentage  
- Analyze impact of venue on results  


## System Architecture

### Database Layer (MySQL)

Three core tables were created:

#### Table 1: `matches`
- match_id (INT)  
- season (INT)  
- team1 (VARCHAR)  
- team2 (VARCHAR)  
- venue (VARCHAR)  
- winner (VARCHAR)  
- match_date (DATE)  

#### Table 2: `players`
- player_id (INT)  
- player_name (VARCHAR)  
- team (VARCHAR)  
- role (VARCHAR)  

#### Table 3: `deliveries`
- match_id (INT)  
- batsman_runs (INT)  
- bowler_runs (INT)  
- is_wicket (INT)  


## Data Preprocessing

Performed in Python using Pandas.

- Removed duplicate records  
- Handled missing values  
- Converted columns to correct data types  
- Created derived column `total_runs`  


## Data Analysis & Dashboard Visualizations

### 1. Team Performance Analysis
- Aggregated total wins by team  
- Analyzed wins by venue and season  
- Visualization: Bar Chart, Pie Chart  
- Purpose: Identify dominant teams and venues  

### 2. Match Insights
- Calculated average runs per match  
- Identified matches with no result  
- Compared home vs away performance  
- Visualization: Line Chart, Bar Chart  
- Purpose: Understand match-level trends  

### 3. Player & Ball Analytics
- Aggregated runs and wickets per match  
- Identified high-scoring matches  
- Visualization: Histogram, Box Plot  
- Purpose: Analyze scoring and bowling patterns  

### 4. Business KPIs
- Calculated top 5 teams by win percentage  
- Analyzed venue impact on match outcomes  
- Visualization: Scatter Plot, Bar Chart  
- Purpose: Evaluate performance efficiency  


## Technologies Used

| Technology | Purpose |
|-----------|--------|
| MySQL | Database storage |
| SQL | Querying and aggregation |
| Python | Data processing |
| Pandas | Data manipulation |
| Matplotlib | Visualization |
| SQLAlchemy | Database connection |
| Git & GitHub | Version control |


## Key Learnings

- Relational database design  
- SQL aggregation and grouping  
- ETL using Pandas  
- Analytical table creation  
- Data visualization techniques  
- GitHub project management  


## Challenges Faced

- Handling missing and inconsistent data  
- Fixing Pandas warnings  
- MySQL connection issues  
- SQL query and schema mismatches  
- GitHub merge conflicts  


## Results & Insights

- Certain teams consistently dominate across seasons  
- Home advantage impacts match outcomes  
- High-scoring matches influence overall trends  
- Venue plays a significant role in results  


## Conclusion

The IPL Analysis – P1 project provides structured analysis of IPL data through database integration, data cleaning, aggregation, and visualization. The project demonstrates practical skills in:

- SQL  
- Python data analysis  
- Data engineering  
- Sports analytics  
- Visualization techniques  


