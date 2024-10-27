# BART (Bay Area Rapid Transit) Ridership

### Project Description

BART, short for "Bay Area Rapid Transit," is the public transit system serving the San Francisco Bay Area. It operates with six routes, 46 stations, and 112 miles of track, serving an average weekday ridership of 423,000 people, making it the fifth-busiest rapid transit system in the United States. This project analyzes ridership data of BART stations in San Francisco using statistical and predictive modeling techniques to answer various analytical questions.

### Dataset

This project uses the [BART Ridership dataset](https://www.kaggle.com/datasets/saulfuh/bart-ridership), which includes daily ridership data for BART stations, covering the years 2016 and 2017.

![San Francisco BART Map](https://metroeasy.com/wp-content/uploads/2023/05/San-Francisco-BART-Map.gif)

### Project Questions

#### Data Analytics Questions:
- Which BART station is the busiest?
- What is the least popular BART route?
- When is the best time to find a seat on a trip from Berkeley to SF?
- Which day of the week is the busiest?
- How many people take the BART late at night?

#### Data Science Questions:
- **Question A**: Compute the straight-line distance between each station.
- **Question B**: Build a model to predict the number of commuters between any two stations.

### Libraries Used

- **pandas**: Data processing and analysis
- **numpy**: Numerical computations
- **matplotlib** and **seaborn**: Data visualization
- **plotly**: Interactive charts
- **geopy**: Geographical computations
- **prophet**: Time series forecasting

### Setup

To run this project, follow these steps:

1. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly geopy prophet
   ```

2. Run the notebook to perform data analytics and predictive analysis.

### Project Structure

- **BART(Bay Area Rapid Transit) Ridership.ipynb**: Jupyter Notebook containing all steps for analysis and modeling.
