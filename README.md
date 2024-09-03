# OpenWeather_Pipeline
An ETL pipeline to move real time weather data from OpenWeather API to Postgres
# Real Time Weather Monitoring - A Modern, User-Centric Weather Application 

Real Time Weather Monitoring consist of Flask-based web application and ETL workflow with Progresql database for Climate weather analysis that provides users with current and clamte weather data for any city in the US. This project, being my first personal venture, has been an enriching experience, providing a deeper understanding of ETL, web development, and databases in Data Science.

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

## Prerequisites

- Python 3.10+
- Flask
- Postgresql
- geopandas
- make_axes_locatable
- OpenWeatherMap API Key

## Installation

1. Clone the repository:
 
 git clone https://github.com/Enimien/WeatherProject

2. Navigate to the clone project directory:
 
 cd WeatherProject
 
3. Install the necessary packages::



## OpenWeatherMap API Key

To fetch the weather data, you'll need an API key from OpenWeatherMap.

1. Sign up for a free account on OpenWeatherMap (if you don't already have one).
2. Generate your API Key.
3. Create a file named .env in the project's root directory.
4. Paste the following information to .env file.
API_KEY = ''
DB_USERNAME=''
DB_PASSWORD=''
DB_HOST ='localhost'
DB_PORT = 5432
DB_NAME = ''
5. Save the file.

## Running the Application

Start the application with the following command:
```md
python -m flask --app app.py run -- for the web application
run US_weather_eda.ipynb -- for the Climate Weather Analysis
```

## How to Use

The application includes the following key features:

1. Home Page ('/'): Displays the Real time monitoring web application.
2. Search Bar: Allows users to find weather forecasts for their desired city.


## Built With

- Flask - The web framework used.
- Postgresql - The database used for ETL Weather Climate Analysis.
- OpenWeatherMap - The API used to get weather data.



This project marks my first step in the exciting journey of ETL Data visualization. I've learned a lot in the process and am eager to learn and build more.

While the Histoical part of the project download 'WeatherEvents_Jan2016-Dec2022.csv' from the link below
 https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events/code 

This part analyzes severe weather event data by plotting the frequency of different types of severe weather events over time. reads the data, identifies unique severe weather types, and then generates a histogram for each weather type, showing the frequency of events over time.
Console Output: A list of severe weather types, e.g., "Types of severe weather: ['Tornado', 'Hail', 'Flood']".
We also   creates choropleth maps that display the frequency of severe weather events across states, providing a visual understanding of the distribution and intensity of these events over time.

#Built with

pandas
matplotlib
geopandas
mpl_toolkits (specifically axes_grid1 for the divider)

 the insight  

