# AirbnbPricePrediction

## Description
This project focuses on developing a predictive model for forecasting the pricing of Airbnb listings before they are made available on the market. By leveraging advanced data analytics and machine learning techniques, the goal is to create a robust algorithm that can analyze various factors influencing the pricing dynamics of Airbnb accommodations. These factors may include location, amenities, number of beds, ... 

There are two usage scenarios for the program:
- When a user wants to list their property on Airbnb, they can use this tool to determine the most appropriate price.
- It allows a user looking to stay in a specific accommodation to check if the property is more expensive than it should be or, on the contrary, a great deal."

## Context of the project

This project was undertaken as part of the Introduction to Data Science course at the University of Skövde in Sweden, during my exchange semester from the University of Technology of Troyes. It is important to note that the project was an individual project, not a group project.

## Dataset

The data is sourced from [Airbnb - Listings](https://public.opendatasoft.com/explore/dataset/airbnb-listings/).
The productor of the dataset is "Inside Airbnb" under a Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license.

The information on the Inside Airbnb site is obtained from publicly available data on the Airbnb platform.

This dataset provides several informations about Airbnb accommodations (price, number of rooms, type of listing, etc.) for several cities in the world. 

The dataset should be downloaded using the provided link then by clicking on the 'Export' tab and selecting 'CSV.' Afterwards, it should be placed in a folder named 'data.' The project structure must follow:
```
notebook.ipynb
data
|- airbnb-listings.csv
```

The dataset describes listings through multiple columns:
- ...

## Setup the Project
0. Ensure you have Python installed on your system. 

1. Clone the repository:
    ```bash
    git clone git@github.com:Antoine-ValentinCharpentier/AirbnbPricePrediction2.git
    cd AirbnbPricePrediction2
    ```

2. Download the dataset and place it as indicated in the Dataset section.
    
3. Initialise the venv:
    ```bash
    python -m venv .venv
    .venv\Scripts\activate OU source .venv/bin/activate
    pip install -r requirements.txt
    ```

4. Execute the script ``notebook.ipynb``
