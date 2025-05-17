# Zomato_data_analysis📊

#📊 Analysis of Zomato Restaurant Data
# Project Highlights
This project analyzes restaurant data from Zomato, focusing on various aspects of the restaurants listed. Here are the key highlights:

Data Loading and Initial Exploration:

The dataset contains 148 restaurants with 7 features: name, online_order, book_table, rate, votes, approx_cost(for two people), and listed_in(type).

Initial data inspection shows a mix of buffet and dining restaurants with varying ratings and costs.

##🛠️ Data Cleaning:

The 'rate' column was cleaned by extracting numerical values from strings (e.g., converting "4.1/5" to 4.1).

Exploratory Data Analysis:

Visualized the distribution of restaurant types using a countplot, showing more buffet restaurants than dining establishments.

Analyzed the relationship between restaurant types and votes received, with buffet restaurants generally receiving more votes.

Identified "Empire Restaurant" as the restaurant with the maximum votes.

##🔍 Key Findings:

Buffet restaurants are more common in the dataset.

Buffet restaurants tend to receive more votes on average.

The most popular restaurant (by votes) is "Empire Restaurant".

Visualizations:

Created a countplot showing the distribution of restaurant types.

Generated a line plot showing the total votes by restaurant type.

Analyzed the distribution of online ordering options among restaurants.

## 📊 Dataset
[Zomato Dataset](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data) (CSV, ~20MB)  
Includes:
- Restaurant names & locations
- Cuisine types
- Average cost for two
- User ratings & votes
- Delivery/booking options

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-orange?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-5.0%2B-green?logo=plotly)
![Folium](https://img.shields.io/badge/Folium-0.14-brightgreen)
