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
- ``ID``: Unique identifier for each listing.
- ``Listing Url``: URL link to the listing.
- ``Scrape ID``: ID associated with the data scrape.
- ``Last Scraped``: Date when the data was last scraped.
- ``Name``: Name of the listing.
- ``Summary``: Short summary or description of the listing.
- ``Space``: Information about the space within the listing.
- ``Description``: Detailed description of the listing.
- ``Experiences Offered``: Type of experiences offered by the host.
- ``Neighborhood Overview``: Overview of the neighborhood where the listing is located.
- ``Notes``: Additional notes about the listing.
- ``Transit``: Information about transportation options in the area.
- ``Access``: Details about guest access to the listing.
- ``Interaction``: Information about interactions with the host.
- ``House Rules``: Rules set by the host for guests.
- ``Thumbnail Url``, ``Medium Url``, ``Picture Url``, ``XL Picture Url``: URLs for various images associated with the listing.
- ``Host ID``: Unique identifier for the host.
- ``Host URL``: URL link to the host's profile.
- ``Host Name``: Name of the host.
- ``Host Since``: Date when the host joined the platform.
- ``Host Location``: Location of the host.
- ``Host About``: Information about the host.
- ``Host Response Time``: Time taken by the host to respond.
- ``Host Response Rate``: Rate of response by the host.
- ``Host Acceptance Rate``: Rate at which the host accepts booking requests.
- ``Host Thumbnail Url``, ``Host Picture Url``: URLs for images associated with the host.
- ``Host Neighbourhood``: Neighborhood of the host.
- ``Host Listings Count``, ``Host Total Listings Count``: Count of listings by the host.
- ``Host Verifications``: Methods used to verify the host's identity.
- ``Street``: Street address of the listing.
- ``Neighbourhood``: General neighborhood information.
- ``Neighbourhood Cleansed``: Cleaned neighborhood information.
- ``Neighbourhood Group Cleansed``: Cleaned neighborhood group information.
- ``City``, ``State``, ``Zipcode``, ``Market``, ``Smart Location``: Location-related information.
- ``Country Code``, ``Country``: Country-related information.
- ``Latitude``, ``Longitude``: Geographic coordinates of the listing.
- ``Property Type``: Type of property (e.g., house, apartment).
- ``Room Type``: Type of room available.
- ``Accommodates``: Number of people the listing can accommodate.
- ``Bathrooms``, ``Bedrooms``, ``Beds``: Number of bathrooms, bedrooms, and beds.
- ``Bed Type``: Type of bed provided.
- ``Amenities``: List of amenities available.
- ``Square Feet``: Area of the listing in square feet.
- ``Price``, ``Weekly Price``, ``Monthly Price``: Pricing information.
- ``Security Deposit``, ``Cleaning Fee``: Deposit and cleaning fee information.
- ``Guests Included``, ``Extra People``: Information about the number of guests included and extra guest fees.
- ``Minimum Nights``, ``Maximum Nights``: Minimum and maximum nights for booking.
- ``Calendar Updated, Has Availability``: Information about the availability of the calendar.
- ``Availability 30``, ``Availability 60``, ``Availability 90``, ``Availability 365``: Availability information for different time periods.
- ``Calendar last Scraped``: Date when the calendar was last scraped.
- ``Number of Reviews``: Total number of reviews.
- ``First Review``, ``Last Review``: Dates of the first and last reviews.
- ``Review Scores Rating``, ``Review Scores Accuracy``, ``Review Scores Cleanliness``, ``Review Scores Checkin``, ``Review Scores Communication``, ``Review Scores Location``, ``Review Scores Value``: Review scores related to different aspects.
- ``License``: Licensing information.
- ``Jurisdiction Names``: Names of jurisdictions.
- ``Cancellation Policy``: Policy for cancellation.
- ``Calculated host listings count``, ``Reviews per Month``: Calculated counts and review frequency.
- ``Geolocation``: Geographical information.
- ``Features``: Additional features associated with the listing.

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
