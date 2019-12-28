# Divvybike-share-Prediction

Predicting number of bikes checked out from the stations every hour/day in an area and classifying a trip as member trip or subscriber trip.

### Data 

Source :

Divvy: https://www.divvybikes.com/system-data   
Weather:     https://www.ncdc.noaa.gov/cdo-web/      

We will be using data set that is provided by DIVVY

Data Each trip is anonymized and includes: 

• Trip start day and time.

• Trip end day and time.

• Trip start station.

• Trip end station.

• Rider type (Member, Single Ride, and Day Pass).

• If a Member trip, it will also include Member’s self-reported gender and year of birth The data has been processed to remove trips that are taken by staff as they service and inspect the system; and any trips that were below 60 seconds in length (potentially false starts or users trying to re-dock a bike to ensure it was secure).


### Classification and Prediction.

We will be using Regression to predict the number of checkouts and classification to predict the trip type as member or subscriber.
We will also be considering weather conditions during our analysis of the data, and how it affects the bike usage.

### Instructions

Dataset is required to run the project which can be downloaded from source link for 2018.

Run the preprocessing notebook first to have clean and merged dataset for futher operations.Please make sure you 
have all the necessary packages (that are imported) to use the project without errors.

