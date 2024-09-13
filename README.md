# Zomato Orders Analysis

This project involves the analysis of Zomato restaurant data from Bangalore, with a focus on understanding the distribution of restaurants offering online ordering services across different locations in the city. The project uses Python for data processing and analysis, primarily leveraging the `pandas` library for data manipulation.

## Project Overview

The goal of this project is to:

- Analyze restaurant data in Bangalore, focusing on their location and online order availability.
- Create insights into which areas have the highest and lowest number of restaurants offering online ordering.
- Provide a pivot table summarizing the data, with each location showing the count of restaurants that offer online orders versus those that don't.

## Dataset

The dataset includes restaurant information from Zomato in Bangalore, with the following key features:
- **Location**: The area in Bangalore where the restaurant is located.
- **Online Order**: A binary variable indicating whether the restaurant offers online ordering (`Yes` or `No`).
- **Name**: The name of the restaurant.

## Files

- `Project 1 for Resume (Zomato Bangalore Order).ipynb`: The Jupyter Notebook containing all the code for data processing and analysis.
- `location_online.csv`: A CSV file generated from the analysis, summarizing the number of restaurants by location and their online ordering availability.

## Technologies Used

- **Python 3.11**
- **Jupyter Notebook**
- **Pandas**: For data manipulation and aggregation.
- **Numpy**: Used for numerical operations.
- **Matplotlib/Seaborn**: (Optional) For data visualization.

## Key Steps

1. **Data Import**: Load the restaurant dataset using `pandas`.
2. **Data Grouping**: Group the dataset by `location` and `online_order` status.
3. **Pivot Table Creation**: Use a pivot table to show the count of restaurants in each location that offer online orders versus those that don't.
4. **Export Results**: The results are exported into `location_online.csv` for further use or visualization.

## Installation and Setup

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
