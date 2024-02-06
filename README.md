# SQL Stolen Vehicles
Utilizing Maven Analytics dataset on New Zealand's stolen vehicle data I completed a series of queries to get a better understanding of the information. 

<p align = "center"> 
  <img src = "https://github.com/jamesbelk0/SQL_Stolen_Vehicles/blob/97ca2fbc3e1208150aeb448a752bdebbe074679b/stolen_vehicles_db.sql">
</p>

### Business problem:

Discover the best market to spend the advertise . 

### Data:
Maven Stolen Vehicle Dataset - https://github.com/jamesbelk0/SQL_Stolen_Vehicles/blob/97ca2fbc3e1208150aeb448a752bdebbe074679b/stolen_vehicles_db.sql

### Data Dictionary:

#### Locations Table:
  * location_id - ID for the individual location
  * region - Name of the region
  * country - Name of the country
  * population - Population size of the region
  * density - Population size compared to the region size
    
#### Make_Details Table:
  * make_id  -ID for the vehicle make
  * make_name - Name of the vehicle make
  * make_type - Is the vehicle luxury or standard

#### Stolen_Vechiles Tables
  * vehicle_id - ID of the vehicle
  * vehicle_type - Type of vehicle
  * make_id - ID for the vehicle make
  * model_year - When the vehicle was made
  * vehicle_desc - Description of the vehicle
  * color - Color of the vehicle
  * date_stolen - When was it stolen, Year-Month-Day
  * location_id - ID for the individual location 

## The Queries were completed to get a better understanding of the dataset. This is the WHEN, WHERE, and WHICH vehicles were stolen.

### Exploratory Data Analysis
    
 - During the exploratory data analysis, a bar chart, a heatmap, and a regional map were all created. 
 - These pivot tables tracked the average income by gender, the customer commute, and the age bracket for the customer.
 
 <p align = "center"> 
  <img src = "https://github.com/jamesbelk0/SQL_Stolen_Vehicles/blob/b0a3181e8927b2c472f0c66ddb20653f78c1a7c6/num_vehicles_stolen_bar.PNG">
</p>

- The chart above shows the breakdown of the stolen vehicles by weekday giving a deeper understanding for law enforcement.
- This shows a large rise of vehicles reported stolen on Monday and Tuesday demonstrating to me that the vehicles would be stolen over the weekend which has the lowest days. 

<p align = "center"> 
  <img src = "https://github.com/jamesbelk0/SQL_Stolen_Vehicles/blob/b0a3181e8927b2c472f0c66ddb20653f78c1a7c6/vehicle_color_heat_map.PNG">
</p>

- The above chart shows a heatmap of the vehicle type including the number of vehicles stolen and what color they are.
- This shows that silver and white vehicles are the majority of the stolen vehicles.
- This also shows that station wagons, saloon and hatchbacks are the most frequently stolen.

<p align = "center"> 
  <img src = "https://github.com/jamesbelk0/SQL_Stolen_Vehicles/blob/b0a3181e8927b2c472f0c66ddb20653f78c1a7c6/new_zealand.PNG">
</p>

- This shows a regional map of New Zealand showing the breakdown of the number of vehicles stolen based by region and a color gradient to show the most prevalent.
- This shows that Auckland, which is also one of the smallest regions has the highest density of stolen vehicles.
  
For any additional questions, please contact **jamesbelk0@gmail.com**
