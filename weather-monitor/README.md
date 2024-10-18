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

  
## Project Structure
![image](https://github.com/user-attachments/assets/d853717c-3a76-4948-8ed5-d5479aec0f77)


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

3. **Run the application**:

     ```python weather_monitor.py
     ```
