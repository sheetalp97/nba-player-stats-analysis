# NBA Player Stats Analysis 2024

## Overview

This project analyzes NBA team and player statistics for the 2022-23 and 2023-24 seasons using web scraping, data cleaning, and visualization techniques. The goal is to predict team win percentages based on player statistics. Linear regression models were built and evaluated. This project was completed as part of the coursework for the "Advanced Software Development with Web Applications" course during my Masters in Information Systems degree in 2024.

## Files

*   `NBA_Player_Stats_Notebook.ipynb`: Google Colab notebook with code for web scraping, data cleaning, analysis, model building, and evaluation.
*   `NBA_Player_Stats_Train.xlsx`: Player and team statistics for the 2022-23 NBA season. Used as the training dataset.
*   `NBA_Player_Stats_Test.xlsx`: Player and team statistics for the 2023-24 NBA season. Used as the testing dataset.

## Data Description

The datasets contain team-level statistics and player-level statistics for the 2022-23 and 2023-24 NBA seasons. Features include team win percentages, player height, weight, age, experience, and various performance metrics.

## Data Sources

*   Basketball Reference (https://www.basketball-reference.com/) (for web scraping)
*   `NBA_Player_Stats_Train.xlsx`
*   `NBA_Player_Stats_Test.xlsx`

## Technologies Used

*   Python
*   Pandas
*   BeautifulSoup
*   Matplotlib
*   Seaborn
*   Statsmodels

## Usage

1.  Clone the repository:

    ```
    git clone https://github.com/sheetalp97/nba-player-stats-analysis
    cd nba-player-stats-analysis
    ```

2.  Open `NBA_Player_Stats_Notebook.ipynb` in Google Colab.
3.  Run the cells sequentially to perform web scraping, data cleaning, analysis, model building, and evaluation.
4.  Note that the `NBA_Player_Stats_Train.xlsx` file is used for training the model, while `NBA_Player_Stats_Test.xlsx` is used for testing/evaluating the model's performance.

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional analyses.
