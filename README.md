# Automatidata
## Background on the Automatidata scenario
Automatidata works with its clients to transform their unused and stored data into useful solutions, such as performance dashboards, customer-facing tools, strategic business insights, and more. They specialize in identifying a client’s business needs and utilizing their data to meet those business needs. 

Automatidata is consulting for the New York City Taxi and Limousine Commission (TLC). New York City TLC is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. The agency has partnered with Automatidata to develop a regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered. 

The TLC data comes from over 200,000 taxi and limousine licensees, making approximately one million combined trips per day. 

## Deliverables
**To improve the learning experience and shorten runtimes**
**The purpose** of this regression model is to find ways to generate more revenue for taxi cab drivers, by regression.
  
**The goal**  is to predict whether or not a customer is a generous tipper, using Machine learning model
<br/>  


## Dataset
> Dataset can be found [Yellow Taxi File](https://github.com/rohanayush/project-automatidata/blob/main/2017_Yellow_Taxi_Trip_Data.csv)

This project uses a dataset called 2017_Yellow_Taxi_Trip_Data.csv. It data gathered by the New York City Taxi & Limousine Commission and published by the city of New York as part of their NYC Open Data program. This is a sample ,drawn from the 113 million rows in the 2017 Yellow Taxi Trip Data table.

**The dataset contains**

**22699 rows – each row represents a different trip**

**18 columns**

#### Dataset Schema 
| Column Name               | Description                                                                                                                                                       |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ID                        | Trip identification number                                                                                                                                        |
| VendorID                  | A code indicating the TPEP provider that provided the record.<br>1= Creative Mobile Technologies, LLC;<br>2= VeriFone Inc.                                       |
| tpep_pickup_datetime      | The date and time when the meter was engaged.                                                                                                                    |
| tpep_dropoff_datetime     | The date and time when the meter was disengaged.                                                                                                                  |
| Passenger_count           | The number of passengers in the vehicle.<br>This is a driver-entered value.                                                                                      |
| Trip_distance             | The elapsed trip distance in miles reported by the taximeter.                                                                                                    |
| PULocationID              | TLC Taxi Zone in which the taximeter was engaged.                                                                                                                 |
| DOLocationID              | TLC Taxi Zone in which the taximeter was disengaged.                                                                                                              |
| RateCodeID                | The final rate code in effect at the end of the trip.<br>1= Standard rate;<br>2=JFK;<br>3=Newark;<br>4=Nassau or Westchester;<br>5=Negotiated fare;<br>6=Group ride |
| Store_and_fwd_flag        | This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server.<br>Y= store and forward trip<br>N= not a store and forward trip                                     |
| Payment_type              | A numeric code signifying how the passenger paid for the trip.<br>1= Credit card;<br>2= Cash;<br>3= No charge;<br>4= Dispute;<br>5= Unknown;<br>6= Voided trip      |
| Fare_amount               | The time-and-distance fare calculated by the meter.                                                                                                              |
| Extra                     | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.                                            |
| MTA_tax                   | $0.50 MTA tax that is automatically triggered based on the metered rate in use.                                                                                 |
| Improvement_surcharge     | $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015.                                              |
| Tip_amount                | Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.                                                            |
| Tolls_amount              | Total amount of all tolls paid in the trip.                                                                                                                       |
| Total_amount              | The total amount charged to passengers. Does not include cash tips.                                                                                                |

### Exploratory Data Analysis
EDA has been carried in [Automatidata eda and testing.ipynb](https://github.com/rohanayush/project-automatidata/blob/main/Automatidata%20eda%20and%20testing.ipynb)

### Regression
Regression has been performed in [Prediction using regression.ipynb](https://github.com/rohanayush/project-automatidata/blob/main/Prediction%20using%20regression.ipynb)

Conclusions:

* Multiple linear regression is a powerful tool to estimate a dependent continous variable from several independent variables.
* Exploratory data analysis is useful for selecting both numeric and categorical features for multiple linear regression.
* Fitting multiple linear regression models may require trial and error to select variables that fit an accurate model while maintaining model assumptions (or not, depending on your use case).

### Modeling
Machine Learning model prediction can be found at [Machine learning.ipynb](https://github.com/rohanayush/project-automatidata/blob/main/Machine%20learning.ipynb)

Different machine learning models were compared to find best prediction, and here are the results:
![](https://res.cloudinary.com/dvfjbyf7s/image/upload/v1703584013/Automatidata/comparisons_modeling.png)




