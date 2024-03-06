# Bike Sharing Dataset Analysis

## Introduction
![Bangkit Academy 2024](images/bangkit.png)

## Running the Streamlit Dashboard

To run the Streamlit dashboard locally, follow these steps:

1. **Create Conda Environment**:
   ```bash
   conda create --name main-ds python=3.9
2. **Activate Conda Environment**:
   ```bash
   conda activate main-ds
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
2. **Run the Streamlit Dashboard**:
   ```bash
   streamlit run dashboard/dashboard.py
### About Me
![Anindya Lokeswara](images/picture.jpeg)
**Anindya Lokeswara**, Machine Learning Cohort at Bangkit Academy 2024. Currently studying computer science at the Faculty of Computer Science, University of Indonesia. Interested in software engineering and data science. Let's connect on [Instagram](https://www.instagram.com/anindyalkwr/) and [LinkedIn](https://www.linkedin.com/in/anindya_lokeswara/).

## Project Overview
This project aims to fulfill the final project requirement from the Dicoding course "Belajar Analisis Data dengan Python".

## Dashboard
You can view the deployed dashboard [here](https://bike-sharing-dashboard-anindyalkwr.streamlit.app/).

### About the Dataset
Bike sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental, and return back has become automatic. Through these systems, users can easily rent a bike from a particular position and return it back at another position. Currently, there are over 500 bike-sharing programs around the world composed of over 500,000 bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental, and health issues.

Apart from interesting real-world applications of bike sharing systems, the characteristics of data being generated by these systems make them attractive for research. Opposed to other transport services such as bus or subway, the duration of travel, departure, and arrival position is explicitly recorded in these systems. This feature turns the bike-sharing system into a virtual sensor network that can be used for sensing mobility in the city. Hence, it is expected that most important events in the city could be detected via monitoring these data.

### Business Questions
- How does daily bike usage vary over time, and which season or month experiences the highest usage?
- Is there a correlation between bike usage and the number of holidays in that season or month?
- What are the mean values of temperature (temp), feels-like temperature (atemp), humidity (hum), and wind speed? How do these factors correlate with the number of daily bike rentals?

## Dataset Information
- `instant`: Record index
- `dteday`: Date
- `season`: Season (1: spring, 2: summer, 3: fall, 4: winter)
- `yr`: Year (0: 2011, 1: 2012)
- `mnth`: Month (1 to 12)
- `hr`: Hour (0 to 23)
- `holiday`: Weather day is holiday or not
- `weekday`: Day of the week
- `workingday`: If day is neither weekend nor holiday is 1, otherwise is 0
- `weathersit`: 
    - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
    - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- `temp`: Normalized temperature in Celsius (values divided by 41, max)
- `atemp`: Normalized feeling temperature in Celsius (values divided by 50, max)
- `hum`: Normalized humidity (values divided by 100, max)
- `windspeed`: Normalized wind speed (values divided by 67, max)
- `casual`: Count of casual users
- `registered`: Count of registered users
- `cnt`: Count of total rental bikes including both casual and registered