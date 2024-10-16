Provide documentation on how to run the project:
markdown
Copy code
# Weather Monitoring System

## Description
This is a real-time weather monitoring system that retrieves data from the OpenWeatherMap API, stores the data in a database, calculates daily rollups and aggregates, checks for alert conditions, and visualizes trends.

## Setup

1. Clone the repository.
2. Install dependencies:
pip install -r requirements.txt
markdown
Copy code
3. Add your OpenWeatherMap API key to `config.py`.
4. Run the application:
python main.py
markdown
Copy code

## Features
- Real-time weather data collection for selected cities in India.
- Daily rollups: average, max, and min temperatures, dominant weather condition.
- Alert system for exceeding temperature thresholds.
- Visualization of daily weather trends.

## Dependencies
- Python 3.x
- `requests`, `schedule`, `sqlite3`, `matplotlib`
