# powerbi-capstone-project - FIFA International Tournament Performance Analysis

## Project Overview

This project is a Power BI capstone project that analyzes the historical performance of national football teams across international tournaments.
The objective is to identify performance trends, compare countries, evaluate win rates, goals scored and conceded, and generate actionable insights
through interactive Power BI dashboards.

## Business Problem

Football analysts, coaches, and sports enthusiasts require a clear understanding of how national teams have performed across multiple tournaments over time.
Raw match data alone provides limited insight.

This project transforms historical tournament data into interactive dashboards that answer key business questions such as:
- Which countries consistently perform best?
- Which teams have the highest win rates?
- How have goals scored changed over time?
- Which teams have the greatest goal difference?
- How has France performed over the last five tournaments?
- Which tournament year recorded the highest points?
- What are the overall win, draw and loss distributions?

The dashboards support performance comparison and data-driven decision making.

## Dataset

Source: International Football Results Dataset

The dataset contains historical international football match records including:
- Tournament Year
- Team
- Goals Scored
- Goals Conceded
- Match Result
- Points Earned

The dataset was cleaned and transformed using Power Query before modelling in Power BI.

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Power BI Service
- GitHub

## Repository Structure

powerbi-capstone-project
│
├── README.md
├── .gitignore
├── dax_measure_library.txt
├── model_diagram.png
│
├── Model
│   └── UJAM_PRECIOUS_PBI_Capstone.pbip
│
├── Documentation
│   └── UJAM_PRECIOUS_PBI_DataDictionary.pdf
│
├── Case study
│   └── UJAM_PRECIOUS_PBI_CaseStudy.pdf
│
└── Visuals
    ├── executive-overview.png
    ├── performance-analysis.png
    └── team-details.png


## Dashboard Pages

### Executive Overview

Provides a high-level summary of tournament performance using KPI cards and trend analysis.

Key metrics include:

- Total Goals
- Total Wins
- Average Goals per Game
- Win Rate
- Tournament Trends

### Performance Analysis

Provides detailed comparisons between countries including:

- Countries with highest and lowest goal difference
- Top 10 Teams by Win Rate
- Total Points by Tournament Year
- Win, Draw and Loss Distribution

### Team Details

Allows users to filter individual teams and evaluate:

- Performance over time
- Tournament participation
- Goals scored
- Goals conceded
- Win trends
- Country-specific statistics

## Key Findings

- Germany recorded one of the highest overall goal totals.
- The Netherlands achieved the highest win rate among the top-performing countries.
- Tournament points generally increased over successive competitions.
- Win percentages exceeded draw percentages across most participating teams.
- Significant differences exist between teams' attacking and defensive performance based on goal difference.

## Recommendations

- Focus future performance analysis on teams with consistently high win rates.
- Monitor long-term goal trends to identify improving or declining national teams.
- Use goal difference alongside total wins when evaluating overall team performance.

## Data Model

The Power BI model follows a structured relational design to improve performance and maintain accurate filtering between tables.

A complete description of all tables, columns, relationships and calculated fields is provided in:

**Documentation/UJAM_PRECIOUS_PBI_DataDictionary.pdf**

## Visual Assets

Dashboard screenshots are available inside the *Visuals* folder.

These include:

- Executive Overview
- Performance Analysis
- Team Details

## LICENSE

This project is licensed under the MIT License and is intended for educational and portfolio purposes.
