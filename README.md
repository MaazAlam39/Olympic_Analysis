# Olympic Data Analysis Web App

## Overview
This project is a Streamlit-based web application that provides comprehensive analysis of Olympic Games data. It offers insights into medal tallies, overall statistics, country-wise performance, and athlete-specific analytics.

## Features
- **Medal Tally**: View and analyze medal counts by year and country.
- **Overall Analysis**: 
  - Display top statistics (editions, hosts, sports, events, athletes, nations)
  - Visualize trends in participating nations, events, and athletes over time
  - Show heatmap of events over time for each sport
  - List most successful athletes across different sports
- **Country-wise Analysis**:
  - Track medal tally over years for a specific country
  - Display heatmap of a country's performance in different sports
  - List top 10 athletes for a selected country
- **Athlete-wise Analysis**:
  - Visualize age distribution of athletes (overall and medal-wise)
  - Show age distribution of gold medalists by sport
  - Plot height vs weight of athletes for different sports
  - Compare men vs women participation over the years

## Technologies Used
- Python
- Streamlit
- Pandas
- Matplotlib
- Seaborn
- Plotly

## Setup and Installation
1. Clone the repository
2. Install the required packages:
    ```
    $pip install -r requirements.txt
    ```
3. Run the Streamlit app:
 ```
    $streamlit run app.py
```

## Data Sources
- `athlete_events.csv`: Contains details about athletes, events, and medals
- `noc_regions.csv`: Mapping of NOC (National Olympic Committee) codes to regions

## Project Structure
- `app.py`: Main Streamlit application file
- `preprocessor.py`: Data preprocessing functions
- `helper.py`: Helper functions for data analysis and visualization
- `notebook/`: Directory containing the dataset CSV files

## How to Use
1. Launch the app using the command mentioned in the Setup section.
2. Use the sidebar to navigate between different analysis sections.
3. Interact with dropdowns and selectors to customize the analysis view.

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check [issues page](insert your issues page link) if you want to contribute.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgements
- Data source: [Kaggle - 120 Years of Olympic History](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)
- Streamlit documentation
- Plotly and Seaborn communities for visualization references