# Flight Delay and Cancellation Analysis

This repository contains an analysis of flight delay and cancellation data. The project involves data cleaning, exploratory data analysis (EDA), 
and visualization to understand flight patterns, delays, and cancellations.

## Dataset
The dataset includes three files:
- `airlines.csv`: Contains airline codes and their corresponding names.
- `airports.csv`: Contains airport information, including their geographic coordinates.
- `flights.csv`: Contains detailed flight information, including delays, cancellations, and routes. 
  
The dataset was extracted from a ZIP file available from: https://www.kaggle.com/datasets/usdot/flight-delays?resource=download&select=flights.csv.

## Project Steps
1. **Data Loading**: The datasets were loaded from a ZIP file and cleaned for missing values.
2. **EDA**:
   - Distribution of delays and cancellations.
   - Relationship between flights and delays across major airports.
   - Monthly delay patterns.
   - Analysis of cancellation rates per airline and airport.
3. **Visualization**: Visualizations were created using `matplotlib` to understand trends in the data.
4. **SQL Queries**: Used DuckDB to analyze the data using SQL queries directly on the DataFrame.

## Visualizations
- **Flight Volume and Delays**: A bar chart with flight volume and a line graph for average delays at top airports.
- **Cancellation Rates**: Bar charts showing the percentage of cancellations by airline and airport.
- **Distance Distribution**: Histogram showing flight distance distribution.

## Tools Used
- **Python**: For data cleaning, analysis, and visualization.
- **Pandas**: For handling and manipulating large datasets.
- **Matplotlib**: For creating visualizations.
- **DuckDB**: For running SQL queries on the dataset.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
