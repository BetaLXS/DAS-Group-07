# Movie Rating Analysis

This repository contains an analysis of movies, focusing on the factors that influence IMDB ratings above 7.
The analysis is based on a dataset of movies that includes attributes such as genre, budget, number of votes, length, and year of release. 
The goal is to understand how these attributes affect the likelihood of a movie having a rating higher than 7.

## Overview

The main goal of this project is to explore how different movie attributes relate to IMDB ratings, particularly those above a score of 7. 
The analysis includes a variety of statistical methods and visualizations to help us understand these relationships.
Key findings include the impact of movie budget, length, and genre on ratings, along with various correlation insights.

## Files in This Repository
- **main.qmd**: The Quarto file used for rendering the analysis and generating the final PDF document.


## Key Steps in the Analysis

1. **Data Preprocessing**: The dataset was cleaned to remove irrelevant columns and handle missing values.
                           Relevant numeric features like budget, votes, and movie length were retained for further analysis.
2. **Visualization**: Several plots were created to visualize the relationships between variables, such as scatterplots for budget vs. IMDB rating and votes vs. rating.
                      A correlation heatmap was also generated to highlight relationships between the variables.
3. **Correlation Analysis**: The correlation between various numeric features was analyzed, particularly focusing on the relationship between budget, length, and the binary rating (ratings above or below 7).
4. **Binary Rating Classification**: A binary classification variable (`rating_binary`) was created, with a threshold set at a rating of 7, to classify movies as having either a low or high rating.
5. **Statistical Testing**: Logistic regression was used to examine the relationships between movie length, budget, and other factors with the binary rating outcome.

   ### Workflow for Contributing:
1. Fork this repository to our own GitHub account.
2. Create a new branch from the main branch for our modifications.
3. Make our own changes to the code or analysis and push the modifications to our own branch.
4. Once our team members have agreed on the changes,we create a pull request to merge your changes into the main branch.
