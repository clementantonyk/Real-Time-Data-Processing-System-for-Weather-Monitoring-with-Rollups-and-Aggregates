

A brief description of what this project does and who it's for

# Real-Time-Data-Processing-System-for-Weather-Monitoring-with-Rollups-and-Aggregates

## Overview
The Weather Application is designed to fetch and store weather data for multiple cities using the OpenWeatherMap API. It provides insights into weather conditions, alerts for high temperatures, and historical weather summaries.

## Features
- **Automated Weather Data Fetching**: Automatically retrieves weather data every 5 minutes for major cities.
- **Temperature Alerts**: Sends alerts when the maximum temperature exceeds a specified threshold (30°C) Celsius for two
 consecutive updates.
- **Data Storage**: Stores weather summaries in a MySQL database for later retrieval.
- **Daily Weather Summaries**: Retrieves the latest weather summaries for the current day.
- **Historical Data Access**: Allows access to recent maximum temperatures for the last 5 days for each city.
- **User-Friendly Interface**: Intuitive UI for users to view current weather conditions and historical data.

## Requirements
- **IDE**: IntelliJ IDEA Ultimate or Visual Studio Code (or any other preferred code editor)
- **Docker**: Mandatory for containerization and deployment
- **Postman**: Optional for API testing and development

## Screenshots

**Weather Monitoring System**

![1](https://github.com/user-attachments/assets/5eebf415-12aa-44a2-8ac4-074669bf6dd3)

**Weather Monitoring System triggering a red alert after the Max temperature exceeded (30°C) Celsius for two
consecutive updates**

- **Alert Overview:** Real-time monitoring triggered an alert due to a temperature threshold breach.

![3](https://github.com/user-attachments/assets/0d6efcff-3725-4998-a61e-e0b5a710942d)

**Weather Monitoring System displays weather data from the past 5 days, which is stored in a database for easy tracking and analysis.**

![2](https://github.com/user-attachments/assets/a7cd3529-09a0-4048-a3ca-3528a61acd79)

## Installation

**Make sure that IDE and Docker is Installed and Opened**

 1. Open a Terminal

 2. Clone the repository by using the command
     
     ```
      git clone [https://github.com/Krish-Depani/Decentralized-Voting-System-Using-Ethereum-Blockchain.git](https://github.com/clementantonyk/Real-Time-Data-Processing-System-for-Weather-Monitoring-with-Rollups-and-Aggregates.git
     ```
     
 3. Navigate to the project directory:
    
    ```
    cd Real-Time-Data-Processing-System-for-Weather-Monitoring-with-Rollups-and-Aggregates
    ``` 

4. Run the following command to start the application:

    ```
    docker-compose up --build
    ```





