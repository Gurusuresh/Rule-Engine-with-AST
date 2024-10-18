# Real-Time Weather Monitoring System

## Project Overview

The **Real-Time Weather Monitoring System** is designed to gather, store, and visualize real-time weather data from multiple cities. It uses APIs to fetch weather data, stores it in a database, and generates summaries, including alerts and visualizations. This project helps monitor weather conditions across cities and provides insightful reports.

## Features

- Fetches real-time weather data for multiple cities.
- Stores weather data in a SQLite database.
- Generates daily summaries including average, maximum, and minimum temperatures.
- Visualizes weather data trends using `matplotlib`.
- Sends email alerts based on custom weather conditions.
- Automatically schedules data fetches at regular intervals.


## Getting Started

### Prerequisites

Before starting, ensure you have:

- Python 3.10 or higher installed
- SQLite (optional for manual inspection of the database)

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Gurusuresh/weather-monitor.git
    cd weather-monitor
    ```

2. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Configure the project**:

   Edit the `config.py` file to add your API key and email settings:

   ```python
   API_KEY = '8f314a8adcccce7a2d05e909d12bbebe'
   DATABASE_URI = 'sqlite:///weather_data.db'
   EMAIL_SENDER = 'ambatigurusuresh88@gmail.com '
   EMAIL_RECEIVER = 'receiver_email@gmail.com'
   EMAIL_PASSWORD = 'your_email_password'
4.**Run the application:

    python weather_monitor.py
    
