# DataSetExploration 
The aim of this assignment is just to explore the dataset and generate insights from it. 

Here is the description of all the variables / features available in the dataset: 

• id - a unique identifier for each trip

• vendor_id - a code indicating the provider associated with the trip record 

• pickup_datetime - date and time when the meter was engaged 

• dropoff_datetime - date and time when the meter was disengaged 

• passenger_count - the number of passengers in the vehicle (driver entered value) 

• pickup_longitude - the longitude where the meter was engaged

• pickup latitude - the latitude where the meter was engaged 

• dropoff_longitude - the longitude where the meter was disengaged 

• dropoff_latitude - the latitude where the meter was disengaged  

• store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle
memory before sending to the vendor because the vehicle did not have a connection to the
server (Y=store and forward; N=not a store and forward trip)  

• trip_duration - (target) duration of the trip in seconds

We performed Data exploration is the first step in data analysis involving the use of data visualization tools and statistical techniques to uncover data set characteristics and initial patterns using  data-exploration techniques to visually explore data sets, look for similarities, patterns and outliers and to identify the relationships between different variables. 
Methods : 

From the EDA we performed in the previous assignment we have the following observations:
id can be removed from dataset because it does not contribute to our model , 'pickup_longitude', 'pickup_latitude', 'dropoff_longitude', 'dropoff_latitude', 'trip_duration' are highly skewed, The same variables have extreme outliers that should be removed
We propose to normalize data, Remove highly corellated variables, Cretae new features duration the idfference between start trip and end trip
