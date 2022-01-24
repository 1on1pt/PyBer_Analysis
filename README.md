# PyBer_Analysis
Exploratory analysis on data to help improve ride share accessibility.
## Overview of the Analysis
As a new data analyst with PyBer, I was tasked with developing an exploratory analysis and creating visualizations by building various charts that would help to tell a story and provide insight on how to boost access to rideshare services and improve affordability in underserved neighborhoods.  Data was provided via two .csv files that contained such metrics as city, date, fare ($USD), ride ID, driver count, and type of city (urban, suburban, and rural).  A summary DataFrame of the ride-sharing data by city type was developed to create a multiple-line graph showing the total weekly fares for each city type.  This analysis was performed writing code script with Python using the Pandas library, Matplotlib, and the Jupyter Notebook and presented to the executive team at PyBer.

### Resources
Data Source:  city_data.csv; ride_data.csv

Code:  PyBer_Challenge.ipynb

Software:  Python 3.7.6; Pandas 1.3.5; Matplotlib; Jupyter Notebook

## Results
PyBer provides ridesharing in diverse locations, including urban, suburban, and rural areas.  In effort to optimize operations, PyBer also collects extensive data as it relates to city, date, fare ($USD), ride ID, driver count, and type of city (urban, suburban, and rural).

Primary differences amongst the data can be observed by comparing the three types of city:
* Urban
* Suburban
* Rural

For instance, the following bubble chart shows that in general, the Urban city type has more drivers, cheaper fares, and a greater total number of rides than Suburban and Rural city types.

![image](https://user-images.githubusercontent.com/94148420/150706409-2d277b89-6b09-42a3-a9fb-e64686e52e1f.png)

In looking at the ride count data by city type, urban is averaging 24.6 rides, suburban is averaging 17.4 rides and rural is averaging 6.9 rides.

![image](https://user-images.githubusercontent.com/94148420/150706881-52e80faf-99ba-4f32-985e-7e2d75571f9c.png)

The percent of total rides is most with urban at 68.4%, followed by suburban at 26.3%, with rural having the lowest at 5.3%.

![image](https://user-images.githubusercontent.com/94148420/150707036-ec888a54-9af3-49e4-bd8e-f3cf16de1c9c.png)

When reviewing the fare data, rural had the highest average fare at $34.62, followed by suburban at $30.97, with urban have the lowest average fare at $24.53.

![image](https://user-images.githubusercontent.com/94148420/150707302-78034d46-cfb6-44de-958f-2b352d35b011.png)

Although rural had the highest average fare, urban had the highest % of total fares by city type with 62.7%, this was followed by suburban at 30.5%, and rural had the lowest at 6.8%.

![image](https://user-images.githubusercontent.com/94148420/150707398-0c9e8fcc-c621-4e46-85f8-f693653d2db9.png)

The driver count data demonstrated that urban had the highest average number of drivers at 36.7 drivers, followed by suburban at an average of 13.7 drivers, with rural having the lowest averagae number of drivers at 4.3 drivers.

![image](https://user-images.githubusercontent.com/94148420/150707886-e3a1af00-9263-4cfe-aa09-f10afba6c0d7.png)

The percent of total drivers correlated directly with the average number of drivers by city type with urban having the greatest percent of total drivers at 80.9%, followed by suburban at 16.5%, with rural having the lowest number of percent total drivers at 2.6%.

![image](https://user-images.githubusercontent.com/94148420/150708086-9a0656dc-3375-482f-92cd-7f42e99aed07.png)

The following is an overall summary of the PyBer ridesharing DataFrame.

![image](https://user-images.githubusercontent.com/94148420/150708816-b2f17fd2-10aa-49bb-acd2-a2f566514fa5.png)

**General findings and trends include:**

1. The urban city type had the highest totals for:
  * Total Rides = 1625
  * Total Drivers = 2405
  * Total Fares = $39,854.38

2. The rural city type had the highest totals for:
  * Average Fare per Ride = $34.62
  * Average Fare per Driver = $55.49

3. From a rider perspective, the **urban average fare** would be most favorable.  This lower average fare could be due to shorter overall distances traveled in the urban setting and a higher volume of total rides.
4. From a driver perpective, the **rural average fare per driver** would be most attractive.  The greater average fare per driver could be due to greater distances traveled by the driver in the rural setting, and thus may be a limiting factor on total rides and a lower volume of total rides.

The multiple-line chart below provides additional visualization of the total fare by city type over the time period of January 2019 to April 2019.  The urban city type had the highest total fare ranging from $1600 to about $2500.  This was followed by the suburban city type, which ranged from about $650 to $1450.  The least fare generating city type for this time period was rural, bringing in a range of about $50 to $500.  Of interest is the fluctuation in total fare over this time period, with all three city types peaking at the same time towards the end of February.

![image](https://user-images.githubusercontent.com/94148420/150714740-5240ddcd-b61b-43a1-a7e4-40eb25056f62.png)

## Summary

This comprehensive analysis and review of the PyBer ridesharing data provides the basis for the following recommendations to the executive team:

1. It appears that the urban city type would support a slight fare increase.  The overall monthly fare total is fairly stable, with the greatest amount of fluctuation occuring during the month of March.
2. Following this same theme, the suburban city type would support a slight fare increase.  The overall monthly fare total is stable, but was beginning to see an increasing trend in the month of April.
3. The data would support trying to recruit and increase the number of drivers for the rural city type.  The rural area had the lowest number of drivers, thus possibly limiting the total number of rides that could be completed.  Increasing the number of drivers could also improve rider satisfaction, improve rider access, cut down on wait times, and possibly lower the average fare per ride (and thus improving affordability for the rural driver).
4. The suburban city type would support an increased number of drivers, thus providing more rides and more overall revenue.  The suburban city type has less than half the total rides of the urban city type, about a fifth of the number of drivers, and about half the revenue.  Increasing the number of suburuban drivers may also help to improve rider access as well as affordability by decreasing the average fare per ride.
5. One final suggestion would be to consider "floating" drivers between the city types during off-peak periods.  For instance, in March, urban drivers could possibly been "floated" to the suburban city type to help pick up any missed rides due to a lack of drivers.  In the same sense, Total Fares were declining at the end of January for the suburban city type as rural Total Fares were increasing.  Suburban drivers could have been "floated" to the rural city type to assist with any potentially missed rides.
