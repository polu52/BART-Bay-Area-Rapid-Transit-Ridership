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

- How would you approach that?

   The project involves a combination of data analytics and machine learning. Initially, I'd clean and preprocess the BART ridership data, ensuring any inconsistencies or missing values are handled. Next, I'd perform exploratory data analysis (EDA) to identify patterns, such as peak usage times, station popularity, and commonly used routes. For the predictive modeling part, I would calculate the straight-line distances between stations and use historical data to forecast ridership trends. A model, such as a time series or regression model, would be trained to predict commuter numbers between stations based on historical data and spatial factors.

- What additional data would you need?

Additional data could enhance the analysis and accuracy of predictions:

   Weather data: Weather impacts commuter behavior, so daily weather data for the Bay Area could help refine the model.
   Event data: Information on events (e.g., sports games, concerts) in the Bay Area could provide context for unusual ridership spikes.
   Socioeconomic factors: Data on neighborhood demographics near stations (e.g., population density, income levels) could offer insights into commuter patterns.
   Transit data from other modes of transportation: Integration with bus, ferry, or other local transit data would help to understand multi-modal commuting patterns.

- How would you want the city or BART officials to use your data?

   I would hope that city or BART officials could use this data to optimize service schedules, reduce overcrowding, and plan for future infrastructure developments. By understanding peak times and popular routes, they could allocate resources more effectively, perhaps increasing train frequency on busy routes. Additionally, forecasting ridership could inform decisions on station maintenance, staffing, and security. This data could also be useful for emergency planning, allowing officials to predict and manage commuter flow during special events or crises.

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
