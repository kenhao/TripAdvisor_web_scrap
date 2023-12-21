# TripAdvisor_web_scrap

## Overview
This GitHub repository contains a series of Jupyter Notebooks designed for scraping hotel information and reviews from **TripAdvisor**. The project is structured into three main parts, each carried out by a separate notebook. The notebooks work in a sequential manner, where the output of one serves as the input for the next.

## Files in the Repository
#### 1. 'TA_hotel_scrap.ipynb' - Scraping Hotel Names
- **Purpose**: This notebook is responsible for scraping the names of all hotels in a specified city from TripAdvisor.
- **Output**: It generates a .npy file containing the list of hotel names, which is used as the input for the next step in the data collection process.


#### 2. 'TA_hotel_info_scrap.ipynb' - Gathering Hotel Information
- **Purpose**: This notebook takes the list of hotel names from the .npy file and scrapes detailed information about each hotel.
- **Output**: The collected data is saved as a .csv file, containing comprehensive details about each hotel.

#### 3. 'TA_review_scrap.ipynb' - Scraping Hotel Reviews
- **Purpose**: The final step in the data collection process, this notebook scrapes customer reviews for each hotel.
- **Output**: Reviews are stored in a .csv file, providing a rich dataset for analysis of customer feedback and experiences.
