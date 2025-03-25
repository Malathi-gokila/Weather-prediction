# Weather Data Fetching and Temperature Prediction

## Overview
This Streamlit-based web application fetches real-time weather data using the OpenWeatherMap API and predicts future temperatures using a linear regression model.

## Features
- Fetches real-time weather data for a given city.
- Displays weather parameters like temperature, humidity, and weather conditions.
- Predicts future temperatures using linear regression.
- Provides a user-friendly interface with Streamlit.

## How It Works
1. The user enters the name of a city in the input field.
2. The application makes an API request to OpenWeatherMap to fetch the latest weather data.
3. The data is processed and displayed, including current temperature, humidity, and weather conditions.
4. Historical temperature data is collected and used to train a linear regression model.
5. The model predicts future temperature trends based on historical patterns.
6. The predictions are visualized using Streamlit, making it easy to interpret.

## Requirements
Ensure you have the following installed:

- Python 3.x
- Streamlit
- Requests
- Pandas
- Scikit-learn

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Nandhu18786/Weather-Prediction.git
   cd Weather-Prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run weather.py
   ```
2. Enter the city name in the input field.
3. View the real-time weather data and predicted temperature trends.

## API Key Setup
To use the OpenWeatherMap API, obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and set it in your environment:
```bash
export WEATHER_API_KEY='your_api_key_here'
```
Or set it directly in the script:
```python
API_KEY = 'your_api_key_here'
```

## Project Structure
```
📂 your-repo
├── weather.py            # Main Streamlit app script
├── requirements.txt      # Required Python libraries
├── README.md             # Documentation
```


