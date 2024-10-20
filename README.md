# Zeotap-Activity2
# Real-Time Weather Monitoring System

## Overview
This project implements a real-time data processing system for monitoring weather conditions across major Indian cities. It retrieves weather data, processes it to generate daily summaries, and triggers alerts for high temperatures. The application is built using Flask and stores data in a SQLite database.

## Features
- **Real-Time Weather Data**: Continuously generates mock weather data for cities in India (Delhi, Mumbai, Chennai, Bangalore, Kolkata, Hyderabad).
- **Database Storage**: Stores daily weather summaries, including average, maximum, and minimum temperatures, along with the dominant weather condition.
- **Alerting System**: Triggers alerts if the temperature exceeds a defined threshold (e.g., 35°C).
- **Web Interface**: Displays the weather summaries in a web application using Flask.

## Installation

### Prerequisites
- Python 3.x
- Flask library
- SQLite (comes pre-installed with Python)

### Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
