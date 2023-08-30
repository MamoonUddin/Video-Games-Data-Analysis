# Video Games Data Analysis
 Analysis DOne on video game sales done with python and SQL.
# Video Game Analysis Project

This repository contains an analysis of video game sales and reviews data. The analysis was conducted using SQL queries and Python scripting. The goal of this project is to gain insights into the relationships between game sales, ratings, and user engagement over different years.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Analysis Tasks](#analysis-tasks)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

The video game industry is a dynamic and evolving space with a diverse range of games being released each year. This project aims to explore and analyze the trends, relationships, and patterns within the video game industry by examining data related to game sales, critic reviews, and user scores.

## Setup

1. **Database Creation**: To start the analysis, an SQLite database named `gamesData.db` was created from the provided CSV data. The database stores information about game sales and reviews.

2. **Python Scripts**: The analysis was performed using Python scripts that executed SQL queries on the database. The `execute_sql_query` function was utilized to streamline the process of executing queries and retrieving results.

## Analysis Tasks

The analysis was divided into several tasks, each focusing on a specific aspect of the data:

- **Exploring Best-Selling Games**: Identifying the top ten best-selling video games based on the number of copies sold.

- **Missing Review Scores**: Determining the count of games missing both critic and user review scores.

- **Years with High Critic Scores**: Finding the years with the highest average critic scores.

- **Critics' and Users' Favorite Years**: Identifying the years that were highly rated by critics and users, respectively.

- **Common High-Rating Years**: Identifying years that excelled in both critic and user ratings, along with the total number of games sold in those years.

- **Identifying an Ideal Value**: Determining a threshold value for further analysis.

## Results

The results of each analysis task were obtained by executing SQL queries and processing the data using Python scripting. Visualizations, such as box plots, were created to represent the distributions and trends within the dataset.

## Conclusion

This project provides insights into the dynamics of the video game industry, including trends in sales, critic and user ratings, and years of high-quality game releases. By systematically analyzing the provided dataset, we were able to uncover meaningful patterns and relationships. This analysis can assist game developers, publishers, and enthusiasts in making informed decisions and understanding the factors that contribute to successful video games.

Feel free to explore the code, queries, and results within this repository to gain a deeper understanding of the analysis process and findings.
