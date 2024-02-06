# SQL Stolen Vehicles
Utilizing Maven Analytics dataset on New Zealand's stolen vehicle data I completed a series of queries to get a better understanding of the information. 

<p align = "center"> 
  <img src = "(https://github.com/jamesbelk0/SQL_Stolen_Vehicles/blob/97ca2fbc3e1208150aeb448a752bdebbe074679b/stolen_vehicles_db.sql)">
</p>

### Business problem:

Discover the best market to spend the advertise . 

### Data:
Maven Stolen Vehicle Dataset - https://github.com/jamesbelk0/Excel-Bike-Data/blob/ed4dec687c78b30098be646ca074cc93ed51ae6f/Excel-Bike-Data.xlsx

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
    
 - During the exploratory data analysis, two line charts and a bar chart were created to help get a better understanding of the data.
 - Before making any analysis I created a new column for age brackets, changed the marital status from M/S to Married/Single, gender from F/M to Male/Female and created three pivot tables. 
 - These pivot tables tracked the average income by gender, the customer commute, and the age bracket for the customer.
 
 <p align = "center"> 
  <img src = "https://github.com/jamesbelk0/Excel-Bike-Data/blob/8d1ea7f3b0702f0656db835f5e40e6300e1f79a7/average_income.PNG">
</p>

The chart above shows the breakdown of the average income of the customer and if they purchased a bike. 

- The data shows that individuals with more income typically purchase bikes.
## Dashboard

<p align = "center"> 
  <img src = "https://github.com/jamesbelk0/Excel-Bike-Data/blob/6bf0f3a385b34fc0bb507af59e94c200835e594f/dashboard.PNG">
</p>

The dashboard above allows for manipulate the data to get a more percise look at an individuals lifestyle. These metrics include Marital Status, Region, Education and if the customer owns a car. 

- The data clearly shows the individuals who make over 50,000 and are middle aged are more likely to purchase a bike. These individuals also will live within 2 miles of work overall with roughly 80 customers who purchase a bike if they are more than 5-10 miles away. 

# Business Solution
 - Using the dashboard above I would recommend for a shop to advertise to the middle aged market and in areas where the average income per household is over 45,000.  
 - My recommendation would be to collect this data and compare findings further expanding our knowledge and preventing possible misdiagnosis in the future. 
For any additional questions, please contact **jamesbelk0@gmail.com**
